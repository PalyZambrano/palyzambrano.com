<script lang="ts">
  import { onMount } from 'svelte';

  import CardGaleria from '$lib/components/CardGaleria.svelte';

  export let title: string;
  export let description: string;
  export let projects: Array<{ title: string; image: string; link: string }>;

  let section: HTMLElement;
  let viewport: HTMLElement;
  let track: HTMLUListElement;
  let sectionHeight = 'auto';
  let translateX = 0;

  onMount(() => {
    const desktop = window.matchMedia('(min-width: 768px)');
    const headerHeight = 80;
    let travel = 0;
    let sectionStart = 0;
    let frame = 0;

    const measure = () => {
      if (!desktop.matches) {
        sectionHeight = 'auto';
        translateX = 0;
        return;
      }

      travel = Math.max(0, track.scrollWidth - viewport.clientWidth);
      sectionStart = section.getBoundingClientRect().top + window.scrollY - headerHeight;
      sectionHeight = `${window.innerHeight - headerHeight + travel}px`;
      update();
    };

    const update = () => {
      if (!desktop.matches) return;
      translateX = -Math.min(Math.max(window.scrollY - sectionStart, 0), travel);
    };

    const onScroll = () => {
      cancelAnimationFrame(frame);
      frame = requestAnimationFrame(update);
    };

    const resizeObserver = new ResizeObserver(measure);
    resizeObserver.observe(track);
    resizeObserver.observe(viewport);
    desktop.addEventListener('change', measure);
    window.addEventListener('resize', measure);
    window.addEventListener('scroll', onScroll, { passive: true });
    measure();

    return () => {
      cancelAnimationFrame(frame);
      resizeObserver.disconnect();
      desktop.removeEventListener('change', measure);
      window.removeEventListener('resize', measure);
      window.removeEventListener('scroll', onScroll);
    };
  });
</script>

<section bind:this={section} class="horizontal-gallery" style:height={sectionHeight}>
  <div class="gallery-sticky">
    <header class="gallery-copy mt-10">
      <h3 class="text-xl uppercase font-semibold">{title}</h3>
      <p class="text-sm md:text-base">{description}</p>
    </header>

    <div bind:this={viewport} class="gallery-viewport">
      <ul
        bind:this={track}
        class="gallery-track"
        style:transform={`translate3d(${translateX}px, 0, 0)`}
      >
        {#each projects as project}
          <li>
            <CardGaleria {...project} />
          </li>
        {/each}
      </ul>
    </div>
  </div>
</section>

<style>
  .gallery-copy {
    width: 91.666667%;
    padding: 2.5rem 0 2rem 2.5rem;
  }

  .gallery-copy p {
    max-width: 42rem;
  }

  .gallery-viewport {
    overflow: hidden;
    padding: 1rem 0;
  }

  .gallery-track {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 1rem;
  }

  @media (min-width: 768px) {
    .gallery-sticky {
      position: sticky;
      top: 80px;
      height: calc(100vh - 80px);
      display: flex;
      flex-direction: column;
      justify-content: center;
      overflow: hidden;
    }

    .gallery-copy {
      width: 50%;
      padding: 0 0 3rem 4rem;
    }

    .gallery-track {
      width: max-content;
      flex-direction: row;
      align-items: center;
      padding: 0 4rem;
      will-change: transform;
    }
  }

  @media (prefers-reduced-motion: reduce) {
    .gallery-track {
      will-change: auto;
    }
  }
</style>
