<script>
  const project = {
    title: 'WEIRD',
    subtitle: 'Ilustración + Diseño Web',
    year: '2025',
    client: 'Erlend Sogge',

    overview:
      'WEIRD es una plataforma que propone recuperar la web como un espacio personal, creativo y humano. Inspirado en los orígenes de Internet —blogs, páginas personales y jardines digitales—, el proyecto se presenta como una alternativa a las redes sociales tradicionales y a la lógica de consumo rápido de contenido.',

    images: [
      {
        url: '/img-brand/weird/portada.png',
        caption: 'portada su'
      }
    ],
    // Fase 1: Ilustraciones
    illustration: {
      title: 'Ilustraciones y gráficos',
      description:
        'Las ilustraciones en WEIRD cumplen un rol narrativo y emocional más que decorativo. A través de personajes, objetos y referencias visuales a la tecnología clásica, el sistema gráfico construye un universo lúdico y nostálgico que refuerza la idea de una web más humana y personal',
      approach:
        'El estilo cartoon, las expresiones amigables y el uso de metáforas visuales permiten explicar conceptos tecnológicos de forma accesible, invitando al usuario a explorar sin intimidación y a sentirse parte de un espacio creativo y propio.',

      gallery: [
        {
          url: '/img-brand/weird/stick.png',
          title: 'stickers'
        },
        {
          url: '/img-brand/weird/shirt.png',
          title: 'camiseta ilustracion'
        },
        {
          url: '/img-brand/weird/sock.png',
          title: 'medias con logo'
        }
      ],

      tools: ['Adobe Illustrator', 'Figma']
    },

    // Fase 2: Desarrollo Web
    development: {
      title: 'Desarrollo Web',
      description:
        'WEIRD permite crear y habitar un espacio personal en la web de forma rápida, simple y autónoma. Combina la facilidad de herramientas modernas con la libertad creativa de los sitios personales de antaño, fomentando una internet más humana y descentralizada.',

      features: [
        {
          name: 'Paleta de color',
          detail:
            'Uso de colores pastel combinados con contrastes fuertes para reforzar el carácter lúdico del proyecto.Gradientes suaves con tonos púrpuras, rosados y amarillos que evocan fantasía, nostalgia y calidez.'
        },
        {
          name: 'Tipografía',
          detail:
            'Tipografía display protagonista para el título WEIRD, con un estilo retro y expresivo.'
        },
        {
          name: 'Ilustración y gráficos',
          detail:
            'Ilustraciones estilo cartoon y elementos gráficos con personalidad propia.Referencias visuales a tecnología “old-school” reinterpretada desde una mirada contemporánea.'
        },
        {
          name: 'Layout',
          detail:
            'Uso de tarjetas, bloques y módulos que simulan piezas coleccionables o páginas personales.'
        }
      ],

      screenshots: [
        {
          url: '/img-brand/weird/weird.png',
          caption: 'landing'
        }
      ],

      stack: {
        frontend: ['HTML/CSS', 'Responsive Design'],
        design: ['Figma', 'Adobe Illustrator']
      }
    },

    // Integración
    integration: {
      title: 'Ilustración + Código',
      description:
        'Las ilustraciones tipo cartas se integran perfectamente en el diseño web, creando una experiencia visual coherente donde cada servicio tiene su propia identidad visual pero mantiene la unidad del conjunto. La paleta violeta atraviesa tanto las ilustraciones como el diseño web, creando una marca visual distintiva y elevada.'
    },

    // Desafío del proyecto
    challenge: {
      title: 'Objetivo',
      description:
        'Esta landing  funcionará como una declaración de principios: más que vender una herramienta, introduce una filosofía de habitar la web de forma consciente, independiente y divertida.',
      requirements: [
        'Presentar WEIRD como una nueva forma de “estar en internet',
        'Comunicar el valor de la identidad digital propia frente a plataformas centralizadas.',
        'Explicar el producto de manera simple, cercana y lúdica.',
        'Conectar emocionalmente con usuarios cansados de las redes sociales tradicionales.'
      ]
    },

    // Concepto visual
    bookingFeature: {
      title: '“Cultivate your personal space on the interwebs”',
      description:
        'El concepto central se apoya en la metáfora del jardín digital: un espacio que se cultiva, crece con el tiempo y refleja la identidad de quien lo habita. WEIRD se aleja de la estética corporativa y adopta un lenguaje visual nostálgico, juguetón y emocional.'
    },

    links: [{ text: 'Ver proyecto', url: 'https://github.com/erlend-sh' }]
  };
</script>

<article class="min-h-screen bg-white">
  <!-- Hero: Split con ilustración -->
  <section class="min-h-screen grid md:grid-cols-2 items-center">
    <div class="px-8 md:px-16 py-16 md:py-0 order-2 md:order-1">
      <span class="text-xs tracking-[0.4em] uppercase mb-6 block">
        {project.year} · {project.client}
      </span>
      <h1
        class="text-4xl md:text-7xl font-light tracking-tight mb-6 leading-tight text-zinc-900"
      >
        {project.title}
      </h1>
      <p class="text-xl md:text-2xl text-violet-900 font-light mb-12">
        {project.subtitle}
      </p>
      <p class="text-base text-zinc-600 leading-relaxed max-w-md">
        {project.overview}
      </p>
    </div>

    <div
      class="relative h-[50vh] md:h-screen order-1 md:order-2 flex items-center justify-center"
    >
      <img
        src={project.images[0].url}
        alt={project.title}
        class="w-full h-full object-cover"
      />
    </div>
  </section>

  <!-- El Desafío -->
  <section class="py-32 px-8 md:px-16">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-3xl md:text-4xl font-light mb-8 text-zinc-900">
        {project.challenge.title}
      </h2>
      <p class="text-xl leading-relaxed text-zinc-700 mb-12 max-w-4xl">
        {project.challenge.description}
      </p>

      <div class="grid md:grid-cols-2 gap-6">
        {#each project.challenge.requirements as requirement}
          <div class="border-l-4 border-violet-500 pl-6 py-4">
            <p class="text-base text-zinc-700">{requirement}</p>
          </div>
        {/each}
      </div>
    </div>
  </section>

  <!-- SECCIÓN: DESARROLLO WEB -->
  <section class="pb-32 bg-violet-50">
    <div class="px-8 md:px-16 mb-20">
      <div class="max-w-6xl mx-auto">
        <h2 class="text-4xl md:text-5xl font-light mb-8 text-zinc-800">
          {project.development.title}
        </h2>
        <p class="text-lg text-zinc-600 leading-relaxed max-w-3xl">
          {project.development.description}
        </p>
      </div>
    </div>

    <!-- Features del desarrollo -->
    <div class="px-8 md:px-16 mb-20">
      <div class="max-w-6xl mx-auto grid md:grid-cols-2 gap-8">
        {#each project.development.features as feature}
          <div class="bg-white py-8 border-t-2 border-violet-500">
            <h3 class="text-xl font-light mb-3 text-zinc-800">
              {feature.name}
            </h3>
            <p class="text-base text-zinc-600 md:pr-4">{feature.detail}</p>
          </div>
        {/each}
      </div>
    </div>

    <!-- Screenshots del sitio -->
    <div class="px-8 md:px-16">
      <div class="max-w-6xl mx-auto space-y-16">
        {#each project.development.screenshots as screenshot, i}
          <div class="grid md:grid-cols-12 gap-8 items-center">
            {#if i % 2 === 0}
              <div class="md:col-span-8 md:col-start-3">
                <img
                  src={screenshot.url}
                  alt={screenshot.caption}
                  class="w-full h-auto shadow-2xl"
                />
              </div>
            {:else}
              <div class="md:col-span-4 order-2 md:order-1">
                <p class="text-sm text-zinc-500">{screenshot.caption}</p>
              </div>
              <div class="md:col-span-8 order-1 md:order-2">
                <img
                  src={screenshot.url}
                  alt={screenshot.caption}
                  class="w-full h-auto shadow-2xl"
                />
              </div>
            {/if}
          </div>
        {/each}
      </div>
    </div>

    <!-- Stack técnico -->
    <div class="px-8 md:px-16 mt-20">
      <div class="max-w-6xl mx-auto grid md:grid-cols-3 gap-12">
        {#each Object.entries(project.development.stack) as [category, items]}
          <div class="bg-white p-8">
            <h3 class="text-xs tracking-[0.3em] uppercase text-violet-600 mb-6">
              {category}
            </h3>
            <ul class="space-y-2">
              {#each items as item}
                <li class="text-sm text-zinc-700">{item}</li>
              {/each}
            </ul>
          </div>
        {/each}
      </div>
    </div>
  </section>

  <!-- SECCIÓN: ILUSTRACIÓN -->
  <section class="py-32 bg-violet-50">
    <div class="px-8 md:px-16 mb-10">
      <div class="max-w-6xl mx-auto">
        <h2 class="text-4xl md:text-5xl font-light mb-8 text-zinc-800">
          {project.illustration.title}
        </h2>
        <div class="grid md:grid-cols-2 gap-6">
          <p class="text-base text-zinc-600 leading-relaxed py-8">
            {project.illustration.description}
          </p>
          <div class="bg-white p-8 border-l-4 border-violet-500">
            <h3 class="text-xs tracking-[0.3em] uppercase text-violet-600 mb-4">
              Enfoque Visual
            </h3>
            <p class="text-base text-zinc-700 leading-relaxed">
              {project.illustration.approach}
            </p>
          </div>
        </div>
      </div>
    </div>

    <!-- Herramientas de ilustración -->
    <div class="px-8 md:px-16 my-10">
      <div class="max-w-6xl mx-auto">
        <h3 class="text-xs tracking-[0.3em] uppercase text-violet-600 mb-6">
          Herramientas
        </h3>
        <div class="flex flex-wrap gap-3">
          {#each project.illustration.tools as tool}
            <span
              class="px-4 py-2 bg-white border border-violet-200 text-sm text-zinc-700"
            >
              {tool}
            </span>
          {/each}
        </div>
      </div>
    </div>

    <!-- Galería de ilustraciones en grid -->
    <div class="px-8 md:px-16">
      <div class="max-w-6xl mx-auto grid md:grid-cols-12">
        {#each project.illustration.gallery as artwork}
          <div
            class="md:col-span-10 md:col-start-2 bg-white p-4 group shadow-lg"
          >
            <div class=" overflow-hidden">
              <img
                src={artwork.url}
                alt={artwork.title}
                class="object-cover transition-transform group-hover:scale-105"
              />
            </div>
          </div>
        {/each}
      </div>
    </div>
  </section>

  <!-- Concepto -->
  <section class="pb-32 px-8 md:px-16 bg-violet-50">
    <div class="max-w-5xl mx-auto">
      <h2 class="text-xl md:text-2xl font-light mb-8">
        {project.bookingFeature.title}
      </h2>
      <p class="text-lg text-zinc-600 mb-12">
        {project.bookingFeature.description}
      </p>
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
