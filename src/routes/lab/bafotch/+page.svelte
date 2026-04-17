<script>
  import SongCard from '$lib/components/SongCard.svelte';

  const project = {
    title: 'BAFOTCH',
    category: 'Ilustración',
    year: '2025',
    description: [
      'Una pieza que traduce identidad en imagen',
      'Para las camisetas de un ballet folclórico tradicional chileno, desarrollé una ilustración que reúne elementos representativos del país de norte a sur, construyendo un relato visual que celebra su diversidad cultural.',
      'A través de símbolos, paisajes y detalles característicos, la gráfica busca conectar con las raíces, reforzando el sentido de pertenencia y la riqueza del folclore. El resultado es una propuesta que no solo viste, sino que también comunica y pone en valor la tradición desde una mirada contemporánea.'
    ]
  };
</script>

<article>
  <!-- Hero Compacto -->
  <section class="px-6 md:px-12 pb-16 w-full">
    <div class="max-w-4xl mx-auto pt-24">
      <div class="flex flex-wrap items-baseline gap-4 mb-8">
        <span class="text-xs tracking-[0.3em] uppercase text-zinc-400">
          {project.category}
        </span>
        <span class="text-xs text-zinc-300">·</span>
        <span class="text-xs tracking-[0.3em] uppercase text-zinc-400">
          {project.year}
        </span>
      </div>
      <h1
        class="text-5xl md:text-7xl font-light tracking-tight mb-8 leading-tight"
      >
        {project.title}
      </h1>
      <div class="space-y-4">
        {#each project.description as paragraph}
          <p class="text-lg md:text-base text-zinc-600 leading-relaxed">
            {paragraph}
          </p>
        {/each}
      </div>
    </div>
  </section>
  <section class="w-full md:w-2/3 px-6 md:px-12 py-16 m-auto">
    <img src="/img-lab/bafotch.png" alt="ilustracion bafotch" />
  </section>
</article>
