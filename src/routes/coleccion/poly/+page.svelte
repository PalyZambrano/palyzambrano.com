<script>
  // Reemplaza con tu información
  const project = {
    title: 'Polyproto',
    category: 'Diseño Web',
    year: '2024',
    description:
      'Polyproto es un proyecto tecnológico open source que propone un sistema descentralizado para la comunicación y el intercambio de datos, donde los usuarios mantienen el control de su identidad y su información',

    // Info básica
    info: [
      { label: 'Cliente', value: 'Flori' },
      { label: 'Duración', value: '3 semanas' },
      { label: 'Rol', value: 'Diseño y Desarrollo' }
    ],

    // Contexto (opcional)
    context:
      'El objetivo del proyecto fue diseñar una landing page que funcionara como punto de entrada al sistema: una interfaz clara y accesible capaz de explicar el funcionamiento general de Polyproto y redirigir a la documentación técnica para quienes quisieran profundizar.El foco estuvo puesto en la interfaz y la comunicación visual, entendiendo la landing como un puente entre un sistema complejo y una primera experiencia comprensible para distintos perfiles de usuario.',

    // Desafío (opcional)
    challenge:
      'El principal desafío fue traducir un sistema técnico complejo en una experiencia visual clara y ordenada, sin simplificar en exceso ni perder rigor conceptual.',

    // Proceso (opcional - 3-4 pasos)
    process: [
      {
        step: 'Comprensión del sistema',
        description:
          'Análisis del funcionamiento de Polyproto y de su documentación técnica para identificar los conceptos clave a comunicar.'
      },
      {
        step: 'Definición de contenidos',
        description:
          'Selección y síntesis de la información esencial para una primera lectura no técnica.'
      },
      {
        step: 'Arquitectura de la información',
        description:
          'Organización del contenido en bloques claros que guían al usuario de lo general a lo específico.'
      },
      {
        step: 'Diseño de interfaz',
        description:
          'Construcción de una interfaz sobria, moderna y funcional, alineada con el carácter tecnológico y open source del proyecto.'
      }
    ],

    // Aprendizaje (opcional)
    learning:
      'Este proyecto reforzó la importancia del diseño de interfaces como herramienta de traducción entre lo técnico y lo humano. Diseñar para sistemas complejos implica no solo pensar en estética, sino en jerarquía, narrativa visual y toma de decisiones conscientes.',

    // Resultado (opcional)
    result:
      'El resultado es una landing page que reduce la barrera de entrada a un sistema técnico complejo, permitiendo entender rápidamente qué es Polyproto y cómo funciona.La interfaz cumple un rol clave dentro del ecosistema del proyecto: contextualizar, explicar y guiar a los usuarios hacia la documentación técnica sin fricción.',

    // Imágenes del proyecto (2-4 imágenes)
    images: [
      {
        url: '/img-brand/poly/mokker.png',
        caption: 'mockup landing'
      },
      {
        url: '/img-brand/poly/mood.png',
        caption:
          ' El concepto visual se inspira en formas que son capaces de transformarse y adaptarse al cambio, como conversaciones cuyos temas cambian constantemente, impulsados ​​por diferentes personas que utilizan distintos canales.'
      },
      {
        url: '/img-brand/poly/landing-web.png',
        caption: 'Landing'
      },
      {
        url: '/img-brand/poly/mock-mobile.png',
        caption: 'Responsive'
      },
      {
        url: '/img-brand/poly/mock-mobile2.png',
        caption: 'Responsive'
      }
    ],

    // Highlights del proyecto (3-5 puntos)
    highlights: [
      'Explicar qué es Polyproto y cómo funciona en pocos segundos.',
      'Ordenar la información para distintos niveles de conocimiento (personas curiosas, desarrolladores y colaboradores).',
      'Diseñar una jerarquía visual que guiara la lectura de forma progresiva.',
      'Generar confianza a través de una interfaz sobria, clara y coherente con los valores del proyecto.'
    ],

    // Stack (opcional)
    stack: ['Figma', 'Svelte', 'Tailwind'],

    // Links externos (opcional)
    links: [{ text: 'Visitar sitio web', url: 'https://polyproto.org' }]
  };
</script>

<article class="min-h-screen bg-white">
  <!-- Hero Compacto -->
  <section class="px-6 md:px-12 pt-24 pb-16">
    <div class="max-w-5xl mx-auto">
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

      <p class="text-lg md:text-xl text-zinc-600 leading-relaxed max-w-3xl">
        {project.description}
      </p>
    </div>
  </section>

  <!-- Info rápida en línea -->
  <section class="px-6 md:px-12 pb-12 border-b border-zinc-200">
    <div class="max-w-5xl mx-auto flex flex-wrap gap-x-12 gap-y-4">
      {#each project.info as item}
        <div class="flex gap-4 items-baseline">
          <span class="text-xs uppercase tracking-wider text-zinc-400">
            {item.label}
          </span>
          <span class="text-sm text-zinc-800">{item.value}</span>
        </div>
      {/each}
    </div>
  </section>

  <!-- mockup landing -->
  <section class="py-12">
    <div class="px-6 md:px-12">
      <div class="max-w-5xl mx-auto">
        <img
          src={project.images[0].url}
          alt={project.images[0].caption}
          class="w-full h-auto"
        />
        {#if project.images[0].caption}
          <p class="text-xs text-zinc-400 mt-4">{project.images[0].caption}</p>
        {/if}
      </div>
    </div>
  </section>

  <!-- Contexto (opcional) -->
  {#if project.context}
    <section class="px-6 md:px-12 py-12 bg-zinc-50">
      <div class="max-w-5xl mx-auto">
        <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-6">
          Contexto
        </h2>
        <p class="text-lg leading-relaxed text-zinc-700">
          {project.context}
        </p>
      </div>
    </section>
  {/if}

  <!-- Desafío (opcional) -->
  {#if project.challenge}
    <section class="px-6 md:px-12 py-12">
      <div class="max-w-5xl mx-auto">
        <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-6">
          Desafío
        </h2>
        <p
          class="text-xl md:text-xl font-light leading-relaxed text-zinc-800 max-w-3xl"
        >
          {project.challenge}
        </p>
      </div>
      <div class="max-w-5xl mx-auto mt-10">
        <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-6">
          Los retos clave fueron:
        </h2>
        <ul class="space-y-3">
          {#each project.highlights as highlight}
            <li class="text-sm text-zinc-700 flex items-start">
              <span class="text-zinc-400 mr-3">—</span>
              {highlight}
            </li>
          {/each}
        </ul>
      </div>
    </section>
  {/if}

  <!-- moodboard -->
  <section class="py-12">
    <div class="px-6 md:px-12">
      <div class="max-w-5xl mx-auto">
        <img
          src={project.images[1].url}
          alt={project.images[1].caption}
          class="w-full h-auto"
        />
        {#if project.images[1].caption}
          <p class="text-xs text-zinc-400 mt-4">{project.images[1].caption}</p>
        {/if}
      </div>
    </div>
  </section>

  <!-- Proceso (opcional) -->
  {#if project.process && project.process.length > 0}
    <section class="px-6 md:px-12 py-16 bg-zinc-50">
      <div class="max-w-5xl mx-auto">
        <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-12">
          Proceso
        </h2>
        <div class="grid md:grid-cols-2 gap-8">
          {#each project.process as step}
            <div>
              <h3 class="text-base font-medium mb-3 text-zinc-800">
                {step.step}
              </h3>
              <p class="text-sm text-zinc-600 leading-relaxed">
                {step.description}
              </p>
            </div>
          {/each}
        </div>
      </div>
    </section>
  {/if}

  <!-- landing -->
  <section class="py-12">
    <div class="px-6 md:px-12">
      <div class="max-w-5xl mx-auto">
        <img
          src={project.images[2].url}
          alt={project.images[2].caption}
          class="w-full h-auto"
        />
        {#if project.images[2].caption}
          <p class="text-xs text-zinc-400 mt-4">{project.images[2].caption}</p>
        {/if}
      </div>
    </div>
  </section>

  <section class="px-6 md:px-12 py-16 bg-zinc-50">
    <div class="max-w-5xl mx-auto grid md:grid-cols-2 gap-12">
      <!-- Stack -->
      {#if project.stack && project.stack.length > 0}
        <div>
          <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-6">
            Stack
          </h2>
          <div class="flex flex-wrap gap-2">
            {#each project.stack as tech}
              <span
                class="px-3 py-1 bg-white border border-zinc-200 text-xs text-zinc-700"
              >
                {tech}
              </span>
            {/each}
          </div>
        </div>
      {/if}
    </div>
  </section>

  <!-- Grid de imágenes secundarias  -->
  {#if project.images.length > 1}
    <section class="px-6 md:px-12 py-16">
      <div class="max-w-5xl mx-auto">
        <div class="grid md:grid-cols-2 gap-8">
          {#each project.images.slice(3) as image}
            <div>
              <img
                src={image.url}
                alt={image.caption}
                class="w-full h-auto mb-4"
              />
              {#if image.caption}
                <p class="text-xs text-zinc-400">{image.caption}</p>
              {/if}
            </div>
          {/each}
        </div>
      </div>
    </section>
  {/if}

  <!-- Aprendizaje (opcional) -->
  {#if project.learning}
    <section class="px-6 md:px-12 py-12 mb-10">
      <div class="max-w-5xl mx-auto">
        <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-6">
          Aprendizaje
        </h2>
        <p class="text-lg leading-relaxed text-zinc-700 max-w-5xl italic">
          {project.learning}
        </p>
      </div>
    </section>
  {/if}

  <!-- Resultado (opcional) -->
  {#if project.result}
    <section class="px-6 md:px-12 py-12 bg-zinc-50">
      <div class="max-w-5xl mx-auto">
        <h2
          class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-6 text-center"
        >
          Resultado
        </h2>
        <p class="text-lg font-light leading-relaxed text-zinc-800 max-w-5xl">
          {project.result}
        </p>
      </div>
    </section>
  {/if}

  <!-- Links/CTA -->
  <section class="py-24 px-8 md:px-16 bg-white">
    <div class="max-w-6xl mx-auto text-center">
      <p class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-8">
        Explorar Proyecto
      </p>
      <div class="flex flex-wrap justify-center gap-4">
        {#each project.links as link}
          <a
            href={link.url}
            target="_blank"
            rel="noopener noreferrer"
            class="inline-block border-2 border-zinc-900 px-8 py-4 text-sm tracking-[0.2em] uppercase hover:bg-zinc-900 hover:text-white transition-colors"
          >
            {link.text} →
          </a>
        {/each}
      </div>
    </div>
  </section>

  <!-- Footer -->
  <section class="px-8 md:px-16 py-16 bg-zinc-50 border-t border-zinc-200">
    <div class="max-w-6xl mx-auto">
      <a
        href="/webdesign"
        class="group inline-flex items-center gap-3 text-sm text-zinc-500 hover:text-zinc-900 transition-colors"
      >
        <span class="group-hover:-translate-x-1 transition-transform">←</span>
        Volver a proyectos
      </a>
    </div>
  </section>
</article>
