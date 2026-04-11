<script>
  const project = {
    title: 'Su Consciencia',
    subtitle: 'Ilustración + Desarrollo Web',
    year: '2025',
    client: 'Susana - Su Consciencia',

    overview:
      'Proyecto integral de diseño y desarrollo web para servicios de astrología y mediumnidad. El sitio integra ilustraciones personalizadas creadas a medida para representar cada servicio, fortaleciendo la experiencia del usuario y construyendo una identidad visual coherente, clara y diferenciadora.',

    images: [
      {
        url: '/img-brand/sucons/mokker-su.png',
        caption: 'portada su'
      }
    ],
    // Fase 1: Ilustraciones
    illustration: {
      title: 'Ilustraciones Estilo Cartas',
      description:
        'El proceso creativo se centró en crear ilustraciones que tuvieran el aspecto de cartas místicas, pero con una estética luminosa y elevada. Cada ilustración representa un servicio específico, funcionando como elementos visuales que comunican la esencia de cada práctica espiritual.',
      approach:
        'Estilo ilustrativo con paleta de violetas y tonos místicos pero luminosos, evitando asociaciones con magia oscura. Cada carta fue diseñada para transmitir espiritualidad, consciencia y elevación.',

      gallery: [
        {
          url: '/img-brand/sucons/mensajesdelalma.png',
          title: 'Carta: Mensajes del Alma',
          description:
            'El prisma de colores representa la iluminación de la conciencia y la fragmentación de las distintas áreas de la vida. Haciendo visible aquello que necesita ser comprendido, integrado y transformado.'
        },
        {
          url: '/img-brand/sucons/medium.png',
          title: 'Carta: Mediumnidad',
          description:
            'La representación gráfica se manifiesta como un puente de estrellas, simbolizando la conexión entre planos, el tránsito de la conciencia y el canal a través del cual se reciben los mensajes espirituales.'
        },
        {
          url: '/img-brand/sucons/alienergetica.png',
          title: 'Carta: Alineación Energética',
          description:
            'La ilustración simboliza los chakras que nos habitan, reflejando el equilibrio y la armonización de la energía interior'
        },
        {
          url: '/img-brand/sucons/terapiafloral.png',
          title: 'Carta: Terapia Floral',
          description:
            'La representación se expresa a través de una flor de loto. Su apertura gradual representa los procesos de transformación y armonización que acompañan el camino terapéutico.'
        },
        {
          url: '/img-brand/sucons/ninointerior.png',
          title: 'Carta: Sanación Niño Interior',
          description:
            'esta ilustración simboliza el reencuentro con la propia esencia, el cuidado consciente y la integración de las experiencias del pasado desde el amor y la contención.'
        },
        {
          url: '/img-brand/sucons/cartaastral.png',
          title: 'Carta: Lectura Carta Astral',
          description:
            'simbolizando el movimiento, la interconexión y la influencia de los astros en los distintos aspectos de la vida'
        }
      ],

      tools: ['Adobe Illustrator', 'Figma']
    },

    // Fase 2: Desarrollo Web
    development: {
      title: 'Desarrollo Web',
      description:
        'Un sitio web diseñado para facilitar que los clientes conozcan los servicios de Susana y agenden sus consultas de forma rápida. La implementación técnica integra las ilustraciones tipo cartas en una experiencia web cohesiva y profesional.',

      features: [
        {
          name: 'Landing con CTA Directos',
          detail:
            'Página principal con botones para agendar cita o contactar por WhatsApp'
        },
        {
          name: 'Catálogo de Servicios Visual',
          detail:
            'Cada servicio representado con su ilustración tipo carta personalizada'
        },
        {
          name: 'Sección Sobre Susana',
          detail: 'Presentación personal que humaniza y genera confianza'
        },
        {
          name: 'Página de Contacto Completa',
          detail:
            'Redes sociales, preguntas frecuentes y múltiples formas de contacto'
        }
      ],

      screenshots: [
        {
          url: '/img-brand/sucons/landing-uno.png',
          caption:
            'La inclusión de ilustraciones animadas con geometría sagrada aporta una dimensión simbólica y energética al sitio, reforzando la conexión espiritual a través del movimiento.'
        },
        {
          url: '/img-brand/sucons/landing-dos.png',
          caption:
            'Las animaciones suaves permiten que las formas se activen y se expandan de manera orgánica, en este caso simulando el movimiento de la luna evocando armonía y transformación, mientras acompañan la experiencia del usuario sin distraerla.'
        },
        {
          url: '/img-brand/sucons/about.png',
          caption:
            'A través de su propia historia, la terapeuta genera un vínculo cercano y empático, invitando a procesos de autoconocimiento, sanación y reconexión con la propia esencia.'
        }
      ],

      stack: {
        frontend: ['HTML/CSS', 'JavaScript', 'Responsive Design'],
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
      title: 'El Desafío',
      description:
        'Diseñar un sitio web que refleje la espiritualidad y el misticismo de la marca desde una estética moderna y consciente, evitando estereotipos visuales asociados a la magia oscura. El sitio debe transmitir confianza, claridad y una experiencia introspectiva que acompañe los servicios de astrología y mediumnidad de Susana.',
      requirements: [
        'Sitio web : Navegación clara e intuitiva, con jerarquías visuales limpias que faciliten la comprensión de los servicios y fomenten la permanencia en el sitio.',
        'Concepto: Fusión de lo místico y lo moderno. El diseño busca transmitir confianza, introspección y renovación, generando una experiencia visual serena y significativa.',
        'Ilustraciones : Texturas Etéreas, con uso de nebulosas y transparencias que remiten al universo y lo cósmico.',
        'Lineamientos Visuales: Orgánico y evolutivo, con líneas suaves y dinámicas que representen transformación y fluidez.'
      ]
    },

    // Funcionalidad de agendamiento
    bookingFeature: {
      title: 'Sistema de Agendamiento Simplificado',
      description:
        'El sitio web está optimizado para la conversión, con múltiples puntos de contacto que facilitan que los visitantes agenden sus consultas.',
      features: [
        'Botón prominente de agendar cita en el hero',
        'Integración directa con WhatsApp para contacto inmediato',
        'Enlaces a sistema de reservas desde cada servicio',
        'Preguntas frecuentes que resuelven dudas antes de agendar'
      ]
    },

    // Resultados
    results: [
      { metric: 'Profesional', label: 'Presencia digital elevada' },
      { metric: 'Violeta', label: 'Identidad visual única' },
      { metric: 'Conversión', label: 'CTAs optimizados' },
      { metric: 'Místico', label: 'Sin estereotipos oscuros' }
    ],

    // Testimonial
    testimonial: {
      quote:
        'Las ilustraciones capturaron perfectamente la esencia de mis servicios sin caer en los clichés oscuros que quería evitar. El sitio web refleja profesionalismo y espiritualidad elevada, justo lo que necesitaba para conectar con mis clientes.',
      author: 'Susana',
      role: 'Fundadora, Su Consciencia'
    },

    links: [{ text: 'Ver sitio web', url: 'https://suconsciencia.com' }]
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
      <div class="max-w-6xl mx-auto grid md:grid-cols-3 gap-4 md:gap-6">
        {#each project.illustration.gallery as artwork}
          <div class="bg-white p-4 group shadow-lg">
            <div class="mb-6 overflow-hidden">
              <img
                src={artwork.url}
                alt={artwork.title}
                class="w-full h-[450px] object-cover transition-transform group-hover:scale-105"
              />
            </div>
            <h3 class="text-lg font-light mb-2 text-zinc-800">
              {artwork.title}
            </h3>
            <p class="text-sm text-zinc-500">{artwork.description}</p>
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
          <div class="bg-white p-8 border-t-2 border-violet-500">
            <h3 class="text-xl font-light mb-3 text-zinc-800">
              {feature.name}
            </h3>
            <p class="text-base text-zinc-600">{feature.detail}</p>
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
              <div class="md:col-span-8">
                <img
                  src={screenshot.url}
                  alt={screenshot.caption}
                  class="w-full h-auto shadow-2xl"
                />
              </div>
              <div class="md:col-span-4">
                <p class="text-sm text-zinc-500">{screenshot.caption}</p>
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

  <!-- Sistema de Agendamiento -->
  <section class="pb-32 px-8 md:px-16 bg-violet-50">
    <div class="max-w-5xl mx-auto">
      <h2 class="text-3xl md:text-4xl font-light mb-8">
        {project.bookingFeature.title}
      </h2>
      <p class="text-lg text-zinc-600 mb-12">
        {project.bookingFeature.description}
      </p>

      <div class="grid md:grid-cols-2 gap-6">
        {#each project.bookingFeature.features as feature}
          <div class="bg-white p-6 flex items-start gap-4">
            <span class="text-violet-500 text-xl">✓</span>
            <p class="text-base text-zinc-700">{feature}</p>
          </div>
        {/each}
      </div>
    </div>
  </section>

  <!-- SECCIÓN: INTEGRACIÓN -->
  <section class="py-32 bg-zinc-50 text-zinc-600">
    <div class="px-8 md:px-16">
      <div class="max-w-4xl mx-auto text-center">
        <h2 class="text-xl md:text-2xl font-light mb-8">
          {project.integration.title}
        </h2>
        <p
          class="text-lg md:text-xl font-light leading-relaxed text-violet-100"
        >
          {project.integration.description}
        </p>
      </div>
    </div>
  </section>

  <!-- Testimonial 
  <section class="py-24 px-8 md:px-16 bg-white">
    <div class="max-w-4xl mx-auto text-center">
      <div class="w-16 h-1 bg-violet-500 mx-auto mb-12" />
      <blockquote
        class="text-lg md:text-xl font-light leading-relaxed italic mb-12 text-zinc-700"
      >
        "{project.testimonial.quote}"
      </blockquote>
      <div>
        <p class="text-lg font-medium text-zinc-900 mb-1">
          {project.testimonial.author}
        </p>
        <p class="text-sm text-zinc-500">{project.testimonial.role}</p>
      </div>
    </div>
  </section> -->

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
