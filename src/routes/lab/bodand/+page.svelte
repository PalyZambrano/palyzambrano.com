<script>
  import SongCard from '$lib/components/SongCard.svelte';

  const project = {
    title: 'Boda N&D',
    category: 'Ilustración',
    year: '2026',
    description: [
      'Una invitación que nace desde el movimiento y la complicidad.',
      'Para la boda de Nelson y Daniela, ambos apasionados por el deporte, desarrollé una pieza ilustrada que captura el origen de su historia: un camino compartido. La escena los muestra ascendiendo una montaña, él corriendo y ella en bicicleta, avanzando juntos en un mismo ritmo, como metáfora de su relación. ',
      'El diseño busca transmitir no solo su vínculo con el deporte, sino también la constancia, el esfuerzo y la conexión que los une, transformando su historia en una narrativa visual sensible y auténtica.'
    ]
  };
</script>

<article class="flex flex-wrap items-center">
  <!-- Hero Compacto -->
  <section class="px-6 md:px-12 pb-16 w-full md:w-1/2">
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
  <section class="w-full md:w-1/2 px-6 md:px-12 py-16 flex justify-center">
    <iframe
      width="470"
      height="679"
      src="https://www.youtube.com/embed/SBTejMtYpK8"
      title="Invitaciones Boda N&amp;D"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
      allowfullscreen
    />
  </section>
</article>
