<script>
  const project = {
    title: 'ROOMY',
    subtitle: 'Make Space',
    year: '2025',
    type: 'Landing Page',
    curator: 'Erlend Sogge',
    overview:
      'Proyecto integral de diseño de landing page para una plataforma de comunicación colaborativa. La propuesta combina ilustración, jerarquía visual y estructura UI para explicar un sistema de conversaciones fluidas, construyendo una experiencia clara, coherente y alineada con los valores del producto.',

    description:
      ' Roomy es una plataforma de comunicación colaborativa que propone una nueva forma de crear, organizar y expandir conversaciones digitales. A diferencia de los sistemas tradicionales de mensajería o foros, Roomy entiende cada interacción como un objeto vivo, capaz de transformarse y evolucionar sin perder contexto.',
    statement:
      'La landing page funciona como la puerta de entrada conceptual al producto: no solo explica qué es Roomy, sino que transmite su filosofía de apertura, fluidez y construcción colectiva.',

    challenge: {
      title: 'Objetivo de landing',
      content:
        'Presentar a Roomy como una alternativa innovadora a las plataformas de comunicación convencionales. Comunicar su enfoque public-first, descentralizado y respetuoso con la privacidad. Generar curiosidad e interés en usuarios con afinidad por tecnología, comunidades digitales y cultura open-source. Explicar conceptos complejos de forma visual y accesible.'
    },

    solution: {
      title: 'Propuesta de valor',
      content:
        'Roomy permite hacer espacio para que las ideas crezcan.Cada mensaje, hilo o post puede expandirse, reorganizarse y mutar según las necesidades del usuario, sin quedar atrapado en estructuras rígidas. La comunicación se concibe como un ecosistema vivo y orgánico.'
    },

    process: [
      {
        phase: '01',
        title: 'Concepto visual',
        description:
          '“Make Space” El concepto se traduce visualmente en un universo ilustrado que representa la expansión de ideas, la convivencia de voces y la creación colectiva. El espacio no es vacío: es fértil, mutable y compartido. Las ilustraciones funcionan como metáforas visuales del sistema',
        image: '/img-brand/roomy/concept.png'
      },
      {
        phase: '02',
        title: 'Resultado esperado',
        description:
          'Una landing inmersiva, memorable y coherente con los valores del proyecto, que posiciona a Roomy como una plataforma experimental, humana y orientada al futuro de la comunicación digital.'
      },
      {
        phase: '03',
        title: 'Paleta de color',
        description:
          'Fondo oscuro predominante (azules y violetas profundos) que refuerza la sensación de espacio, profundidad y tecnología. En ilustraciones colores cálidos, saturados y acentos para transmitir energía, vida y movimiento.',
        image: '/img-brand/roomy/color-roomy.png'
      },
      {
        phase: '04',
        title: 'Layout',
        description:
          'Composición vertical con bloques bien diferenciados. Ritmo visual que alterna texto breve + apoyo gráfico. Espacios amplios que refuerzan el concepto de fluidez y expansión.'
      },
      {
        phase: '05',
        title: 'Público objetivo',
        description:
          'Personas vinculadas a: Tecnología y desarrollo, Comunidades digitales y open-source, Creadores de contenido, investigadores y colectivos colaborativos. Usuarios con mentalidad exploradora, interés por nuevas formas de interacción online y sensibilidad por el diseño y la narrativa visual.',
        image: '/img-brand/roomy/user-roomy.png'
      }
    ],

    images: [
      {
        url: '/img-brand/roomy/portada.png',
        caption: 'portada'
      },
      {
        url: '/img-brand/roomy/fondo.png',
        caption: 'Cartel'
      }
    ],
    brandAssets: [
      { url: '/img-brand/roomy/landing-roomy.png', caption: 'Landing' }
    ],

    nextProject: {
      title: 'Próximo Proyecto',
      name: 'Siguiente proyecto',
      link: '/poly'
    },

    links: [{ text: 'Ver proyecto', url: 'https://github.com/erlend-sh' }]
  };
</script>

<article class="min-h-screen bg-white">
  <!-- Hero: Título a la izquierda, Info a la derecha -->
  <section class="min-h-screen grid md:grid-cols-2">
    <!-- Columna izquierda: Título -->
    <div class="flex flex-col justify-center px-8 md:px-16 py-24 md:py-0">
      <span class="text-xs tracking-[0.4em] uppercase text-zinc-400 mb-8">
        {project.type} · {project.year}
      </span>
      <h1
        class="text-7xl md:text-8xl font-light tracking-tight leading-none mb-8"
      >
        {project.title}
      </h1>
      <p class="text-xl text-zinc-600 leading-relaxed mb-12">
        {project.subtitle}
      </p>
      <div class="space-y-4 text-sm mb-4">
        <div class="flex gap-4">
          <span class="text-zinc-400 w-24">Cliente</span>
          <span class="text-zinc-800">{project.curator}</span>
        </div>
      </div>
      <p class="text-base text-zinc-600 leading-relaxed max-w-md">
        {project.overview}
      </p>
    </div>

    <!-- Columna derecha: Imagen principal -->
    <div class="relative h-screen">
      <img
        src={project.images[0].url}
        alt={project.title}
        class="w-full h-full object-cover object-top"
      />
    </div>
  </section>

  <!-- Texto flotante sobre imagen -->
  <section class="relative">
    <div class="absolute inset-0">
      <img
        src={project.images[1].url}
        alt="Background"
        class="w-full h-full object-cover opacity-10"
      />
    </div>
    <div class="relative py-32 px-8 md:px-16">
      <div class="max-w-3xl mx-auto">
        <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-8">
          Contexto
        </h2>
        <p class="text-lg md:text-xl font-light leading-relaxed text-zinc-800">
          {project.description}
        </p>
      </div>
    </div>
  </section>

  <!-- Desafío y Solución: Grid asimétrico -->
  <section class="grid md:grid-cols-2 gap-px bg-zinc-200 mt-14">
    <!-- Desafío: 1 columna -->
    <div class="bg-white p-12 md:p-16">
      <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-8">
        {project.challenge.title}
      </h2>
      <p class="text-base leading-relaxed text-zinc-700">
        {project.challenge.content}
      </p>
    </div>

    <!-- Solución: 2 columnas -->
    <div class="bg-white p-12 md:p-16 md:col-span-1">
      <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-8">
        {project.solution.title}
      </h2>
      <p class="text-base leading-relaxed text-zinc-700 mb-12">
        {project.solution.content}
      </p>
    </div>
  </section>

  <!-- Statement con borde lateral -->
  <section class="py-24 px-8 md:px-16 bg-zinc-50">
    <div class="max-w-4xl border-l-4 border-zinc-300 pl-8">
      <p class="text-lg leading-relaxed text-zinc-700 italic">
        {project.statement}
      </p>
    </div>
  </section>

  <!-- Proceso: Layout de revista con imágenes grandes -->
  <section class="pt-32">
    <div class="px-8 md:px-16 mb-24">
      <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400">Proceso</h2>
    </div>

    {#each project.process as step, i}
      {#if i % 2 === 0}
        <!-- Layout: Texto a la izquierda, imagen a la derecha -->
        <div class="px-8 md:px-16 mb-32">
          <div class="grid md:grid-cols-2 gap-16 items-end">
            <div>
              <span class="text-7xl font-light text-zinc-200 block mb-6"
                >{step.phase}</span
              >
              <h3 class="text-2xl font-light mb-6 text-zinc-800">
                {step.title}
              </h3>
              <p class="text-base text-zinc-600 leading-relaxed">
                {step.description}
              </p>
            </div>
            <img
              src={step.image}
              alt={step.title}
              class="w-3/4 m-auto object-cover"
            />
          </div>
        </div>
      {:else}
        <!-- Layout: Imagen full width arriba, texto abajo en dos columnas -->
        <div class="mb-32">
          <div class="px-8 md:px-16 grid md:grid-cols-12 gap-12">
            <div class="md:col-span-2">
              <span class="text-7xl font-light text-zinc-200">{step.phase}</span
              >
            </div>
            <div class="md:col-span-4">
              <h3 class="text-2xl font-light mb-4 text-zinc-800">
                {step.title}
              </h3>
            </div>
            <div class="md:col-span-6">
              <p class="text-base text-zinc-600 leading-relaxed">
                {step.description}
              </p>
            </div>
          </div>
        </div>
      {/if}
    {/each}
  </section>

  <!-- Sistema de Identidad - Grid masonry -->
  <section class="bg-white text-zinc-900 pb-16">
    <div class="max-w-6xl mx-auto px-6 md:px-16">
      <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-16">
        Sistema de Identidad Visual
      </h2>

      <div class="space-y-6">
        {#each project.brandAssets as asset}
          <div class="group">
            <img
              src={asset.url}
              alt={asset.caption}
              class="w-full h-auto mb-4 transition-transform group-hover:scale-[1.02]"
            />
          </div>
        {/each}
      </div>
    </div>
  </section>

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
