<script>
  import SongCard from '$lib/components/SongCard.svelte';

  const project = {
    title: 'Endurance by Achira',
    category: 'Confeccion de prendas',
    year: '2025',
    description: [
      'La colaboración entre Achira y el gimnasio surge a partir del interés del cliente por incorporar dentro de su identidad un modelo de camiseta previamente desarrollado por la marca. Esta elección responde tanto a la funcionalidad comprobada de la prenda como a su estética, ya validada en el universo Achira. El proyecto se centra en adaptar este diseño existente a las necesidades del gimnasio, integrando su identidad visual sin perder la esencia original de la prenda. De esta forma, se genera un cruce entre un producto consolidado y una nueva aplicación contextual.',
      'Además, el gimnasio enfrentaba una problemática concreta: la dificultad de encontrar camisetas institucionales deportivas diseñadas específicamente para mujeres. Las opciones disponibles en el mercado eran mayoritariamente unisex, lo que se traducía en prendas poco cómodas, con calces inadecuados y sin considerar las necesidades reales de las entrenadoras.'
    ],
    objective: [
      'Adaptar un modelo de camiseta existente de Achira para su uso en el contexto del gimnasio, incorporando su identidad de marca y resolviendo una necesidad específica del usuario final.',
      ' Se buscó:',
      'Ofrecer una alternativa real a las camisetas unisex, mediante un diseño pensado para el cuerpo femenino.',
      'Mantener la funcionalidad y calce del modelo original, previamente testeado.',
      'Integrar el logo del gimnasio de manera armónica dentro de la prenda.',
      'La paleta cromática de Achira se mantiene como eje del proyecto, proponiendo un sistema flexible donde cada entrenadora puede apropiarse de la prenda y combinarla libremente, manteniendo al mismo tiempo una identidad visual común.'
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
  <section class="max-w-4xl mx-auto">
    <img src="/img-lab/colabend/ficha.png" alt="" />
  </section>
  <section class="px-6 md:px-12 pb-16 w-full">
    <div class="max-w-4xl mx-auto pt-24">
      <div class="space-y-4">
        <span class="text-xs tracking-[0.3em] uppercase text-zinc-400">
          Objetivo
        </span>
        {#each project.objective as paragraph}
          <p class="text-lg md:text-base text-zinc-600 leading-relaxed">
            {paragraph}
          </p>
        {/each}
      </div>
    </div>
  </section>
  <section class="grid md:grid-cols-2 gap-4 max-w-4xl mx-auto mt-10 p-4">
    <img src="/img-lab/colabend/prensa.jpeg" alt="cartel bienbenidos" />
    <img src="/img-lab/colabend/dtf.jpg" alt="ilustracion invitacion" />
  </section>
  <section class="max-w-4xl mx-auto grid grid-cols-5 my-12">
    <div class="bg-[#9F5FA0] h-10" />
    <div class="bg-[#FFD3ED] h-10" />
    <div class="bg-[#E052A5] h-10" />
    <div class="bg-[#B0D2F9] h-10" />
    <div class="bg-black h-10" />
  </section>

  <section class="grid md:grid-cols-2 gap-4 max-w-4xl mx-auto mt-10 pb-20">
    <img src="/img-lab/colabend/resultado.jpg" alt="cartel bienbenidos" />
    <div class="bg-zinc-100 flex items-center justify-center">
      <p
        class="text-base md:text-base text-zinc-600 leading-relaxed px-10 text-center"
      >
        El resultado es una solución concreta que responde a una necesidad poco
        atendida en el mercado, combinando diseño, funcionalidad y
        personalización para mejorar la experiencia diaria de las entrenadoras.
      </p>
    </div>
  </section>
</article>
