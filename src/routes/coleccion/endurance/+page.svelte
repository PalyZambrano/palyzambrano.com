<script>
  // Reemplaza con tu información
  const project = {
    title: 'Ecosistema Digital Completo',
    tagline: 'App Web · Sitio Web · Social Media',
    year: '2024',
    client: 'Endurance',
    duration: '3 meses',

    // Overview del proyecto
    overview: {
      description:
        'Un ecosistema digital integral que abarca desde la aplicación web hasta la presencia en redes sociales. Cada plataforma fue diseñada para funcionar de manera independiente pero mantener una identidad visual cohesiva.',
      challenge:
        'Crear una experiencia consistente a través de múltiples plataformas mientras se respeta las particularidades y mejores prácticas de cada medio.'
    },

    // Roles y equipo
    team: [
      { role: 'Diseño UI/UX', name: 'Paly Zambrano' },
      { role: 'Desarrollo', name: 'Leo Borai' }
    ],

    // DELIVERABLE : App Web
    webapp: {
      title: 'App Web',
      subtitle: 'Dos Interfaces, Un Ecosistema',
      description:
        'El sistema se divide en dos experiencias diferenciadas pero interconectadas. Por un lado, los miembros del gimnasio interactúan con una interfaz limpia e intuitiva donde reservar una clase es tan simple como tres taps. Mientras tanto, el equipo administrativo cuenta con un sistema completo que les permite visualizar la ocupación en tiempo real, gestionar múltiples clases simultáneamente y acceder a reportes que optimizan la toma de decisiones operativas.',

      screenshots: [
        {
          url: '/img-brand/endurance/client-admin.png',
          caption: 'Vistas de calendario y gestión de clases'
        },
        {
          url: '/img-brand/endurance/client-user.png ',
          caption: 'Interfaz de usuario con acceso a reservas'
        }
      ],

      stack: ['Figma', 'Tailwind CSS', 'Svelte']
    },

    // Investigación de Usuarios
    research: {
      title: 'Gestión de reservas para usuarios',
      description:
        'Para entender mejor las necesidades y expectativas de los usuarios, se llevaron a cabo entrevistas y encuestas a un grupo de miembros del gimnasio con distintos niveles de experiencia tecnológica.',

      findings: [
        {
          insight: 'Gestión eficiente',
          description:
            'Los administradores necesitaban herramientas eficaces para gestionar horarios, clases y usuarios.'
        },
        {
          insight: 'Necesidad de flexibilidad',
          description:
            'Los usuarios querían poder reservar, cancelar y reprogramar sus sesiones fácilmente.'
        },
        {
          insight: 'Interfaz intuitiva',
          description:
            'La app debía ser fácil de usar, incluso para aquellos con poca experiencia en tecnología tomando en cuenta las distintas edades de los usuarios.'
        }
      ]
    },

    // DELIVERABLE : Sitio Web
    website: {
      title: 'Sitio Web',
      subtitle: 'Acceso multiplataforma y presencia digital',
      description:
        'Un sitio web desarrollado para permitir a los usuarios acceder a sus reservas desde cualquier dispositivo con conexión a Internet. Incluye información sobre el gimnasio, programas y tarifas, complementando la experiencia de la app móvil.',

      sections: [
        {
          name: 'Información del Gimnasio',
          detail: 'Presentación completa de instalaciones y servicios'
        },
        {
          name: 'Programas y Clases',
          detail: 'Catálogo detallado de entrenamientos disponibles'
        },
        {
          name: 'Tarifas y Planes',
          detail: 'Información clara sobre membresías y precios'
        },
        {
          name: 'Sistema de Reservas Web',
          detail: 'Acceso completo a la gestión de cupos desde navegador'
        }
      ],

      screenshots: [
        {
          url: '/img-brand/endurance/landing.png',
          caption: 'Hero - bienvenida con video'
        },
        {
          url: '/img-brand/endurance/landing2.png',
          caption: 'Tipos de clases y especificaciones'
        },
        {
          url: '/img-brand/endurance/landing3.png',
          caption: 'Ilustracion mapa del lugar'
        }
      ],

      stack: ['Figma', 'Tailwind CSS', 'Svelte']
    },

    // DELIVERABLE : Panel de Administración
    admin: {
      title: 'Panel de Administración',
      subtitle: 'Herramientas de gestión para el gimnasio',
      description:
        'Sistema completo para que los administradores gestionen horarios, clases, usuarios y obtengan insights valiosos sobre la operación del gimnasio.',

      platforms: [
        {
          name: 'Dashboard Principal',
          focus: 'Vista general de la operación diaria',
          formats: [
            'Calendario semanal',
            'Calendario mensual',
            'Vista de reservas'
          ],
          frequency: 'Actualización en tiempo real'
        },
        {
          name: 'Gestión de Clases',
          focus: 'Administración de horarios y capacidad',
          formats: [
            'Crear clases',
            'Modificar horarios',
            'Asignar instructores'
          ],
          frequency: 'Gestión continua'
        },
        {
          name: 'Estadísticas y Reportes',
          focus: 'Análisis de ocupación y tendencias',
          formats: [
            'Reportes de asistencia',
            'Ocupación de clases',
            'Análisis de usuarios'
          ],
          frequency: 'Reportes semanales/mensuales'
        }
      ],

      deliverables: [
        'Calendario completo de reservas',
        'Dashboard de gestión intuitivo',
        'Sistema de reportes y estadísticas',
        'Gestión de usuarios y clases',
        'Herramientas de optimización de recursos'
      ]
    },

    // DELIVERABLE : Social Media
    social: {
      title: 'Social Media Templates',
      subtitle: 'Sistema de contenido para redes sociales',
      description:
        'Un conjunto de plantillas diseñadas para mantener consistencia visual en todas las plataformas sociales.',

      gallery: [
        {
          url: '/img-brand/endurance/general-post.png',
          caption: 'Template Instagram Post'
        },
        {
          url: '/img-brand/endurance/run-post.png',
          caption: 'Template Instagram Story'
        },
        {
          url: '/img-brand/endurance/cycling-post.png',
          caption: 'Template LinkedIn'
        },
        {
          url: '/img-brand/endurance/horario-nuevo.png',
          caption: 'Template Twitter'
        },
        {
          url: '/img-brand/endurance/valores.png',
          caption: 'Carrusel educativo'
        },
        {
          url: '/img-brand/endurance/musica-end.png',
          caption: 'Post de anuncio'
        }
      ]
    },

    // Sistema de diseño
    designSystem: {
      title: 'Sistema de Diseño Unificado',
      description:
        'Todo el ecosistema comparte un sistema de diseño coherente que garantiza consistencia visual y facilita la escalabilidad del proyecto.'
    },

    // Links
    links: [{ text: 'Visitar Sitio Web', url: 'https://endurancetrainning.cl' }]
  };
</script>

<article class="min-h-screen bg-white">
  <!-- Hero Full Width -->
  <section
    class="relative min-h-min py-32 flex items-center justify-center bg-zinc-900 text-white overflow-hidden"
  >
    <div class="absolute inset-0 opacity-10">
      <div
        class="absolute top-20 left-10 w-64 h-64 bg-blue-500 rounded-full blur-3xl"
      />
      <div
        class="absolute bottom-20 right-10 w-96 h-96 bg-purple-500 rounded-full blur-3xl"
      />
    </div>

    <div class="relative z-10 px-8 md:px-16 text-center max-w-5xl">
      <p class="text-xs tracking-[0.4em] uppercase text-zinc-400 mb-8">
        {project.year} · {project.title}
      </p>
      <h1
        class="text-6xl md:text-8xl font-light tracking-tight mb-8 leading-tight"
      >
        {project.client}
      </h1>
      <p class="text-2xl md:text-3xl font-light text-zinc-300 mb-4">
        {project.tagline}
      </p>
    </div>
  </section>

  <!-- Overview -->
  <section class="py-32 px-8 md:px-16">
    <div class="max-w-6xl mx-auto grid md:grid-cols-2 gap-16">
      <div>
        <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-6">
          El Proyecto
        </h2>
        <p class="text-xl md:text-2xl font-light leading-relaxed text-zinc-700">
          {project.overview.description}
        </p>
      </div>
      <div class="bg-zinc-50 p-10">
        <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-6">
          El Desafío
        </h2>
        <p class="text-base leading-relaxed text-zinc-700">
          {project.overview.challenge}
        </p>
      </div>
    </div>
  </section>

  <!-- Separador con número -->
  <div class="border-t border-zinc-200 py-4">
    <div class="max-w-6xl mx-auto px-8 md:px-16">
      <span class="text-xs tracking-[0.3em] uppercase text-zinc-400"
        >01 de 03</span
      >
    </div>
  </div>

  <!-- DELIVERABLE 1: SITIO WEB -->
  <section class="py-32 px-8 md:px-16">
    <div class="max-w-6xl mx-auto">
      <!-- Header -->
      <div class="mb-20">
        <div class="flex items-baseline gap-4 mb-6">
          <span class="text-7xl font-light text-zinc-200">01</span>
          <div>
            <h2 class="text-4xl md:text-5xl font-light mb-2 text-zinc-800">
              {project.website.title}
            </h2>
            <p class="text-xl text-zinc-500">{project.website.subtitle}</p>
          </div>
        </div>
        <p class="text-lg leading-relaxed text-zinc-600 max-w-3xl">
          {project.website.description}
        </p>
      </div>

      <!-- Secciones del sitio -->
      <div class="grid md:grid-cols-2 gap-6 mb-20">
        {#each project.website.sections as section}
          <div class="border-l-4 border-zinc-300 pl-6 py-4">
            <h3 class="text-lg font-light mb-2 text-zinc-800">
              {section.name}
            </h3>
            <p class="text-sm text-zinc-600">{section.detail}</p>
          </div>
        {/each}
      </div>

      <!-- Screenshots alternados -->
      <div class="space-y-20 mb-20">
        {#each project.website.screenshots as screenshot, i}
          <div class="grid md:grid-cols-12 gap-8 items-center">
            {#if i % 2 === 0}
              <div class="md:col-span-8">
                <img
                  src={screenshot.url}
                  alt={screenshot.caption}
                  class="w-full h-auto shadow-xl"
                />
              </div>
              <div class="md:col-span-4" />
            {:else}
              <div class="md:col-span-4 order-2 md:order-1" />
              <div class="md:col-span-8 order-1 md:order-2">
                <img
                  src={screenshot.url}
                  alt={screenshot.caption}
                  class="w-full h-auto shadow-xl"
                />
              </div>
            {/if}
          </div>
        {/each}
      </div>

      <!-- Stack -->
      <div class="mt-16 pt-16 border-t border-zinc-200">
        <h3 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-6">
          Stack Técnico
        </h3>
        <div class="flex flex-wrap gap-3">
          {#each project.website.stack as tech}
            <span class="px-4 py-2 bg-zinc-900 text-white text-sm">
              {tech}
            </span>
          {/each}
        </div>
      </div>
    </div>
  </section>

  <!-- Separador con número -->
  <div class="border-t border-zinc-200 py-4">
    <div class="max-w-6xl mx-auto px-8 md:px-16">
      <span class="text-xs tracking-[0.3em] uppercase text-zinc-400"
        >02 de 03</span
      >
    </div>
  </div>

  <!-- DELIVERABLE 2: APP WEB -->
  <section class="py-32 px-8 md:px-16 bg-gradient-to-b from-white to-zinc-50">
    <div class="max-w-6xl mx-auto">
      <!-- Header -->
      <div class="mb-20">
        <div class="flex items-baseline gap-4 mb-6">
          <span class="text-7xl font-light text-zinc-200">02</span>
          <div>
            <h2 class="text-4xl md:text-5xl font-light mb-2 text-zinc-800">
              {project.webapp.title}
            </h2>
            <p class="text-xl text-zinc-500">{project.webapp.subtitle}</p>
          </div>
        </div>
        <p class="text-base leading-relaxed text-zinc-600">
          {project.webapp.description}
        </p>
      </div>

      <!-- parte 1 -->
      <div class="max-w-6xl mx-auto py-10">
        <div class="mb-20">
          <div class="flex items-baseline gap-4 mb-6">
            <div>
              <h2 class="text-2xl md:text-2xl font-light mb-2 text-zinc-800">
                {project.admin.title}
              </h2>
            </div>
          </div>
          <p class="text-lg leading-relaxed text-zinc-600 max-w-3xl">
            {project.admin.description}
          </p>
        </div>

        <div class="grid md:grid-cols-3 gap-8 mb-20">
          {#each project.admin.platforms as platform}
            <div class="bg-white p-8 border border-zinc-200">
              <h3 class="text-xl font-light mb-6 text-zinc-800">
                {platform.name}
              </h3>
              <p class="text-sm text-zinc-600 mb-6 italic">{platform.focus}</p>
              <ul class="space-y-2 mb-6">
                {#each platform.formats as format}
                  <li class="text-sm text-zinc-600 flex items-start">
                    <span class="text-zinc-400 mr-2">•</span>
                    {format}
                  </li>
                {/each}
              </ul>
              <p class="text-xs text-zinc-500">{platform.frequency}</p>
            </div>
          {/each}
        </div>

        <!-- Screenshots -->
        <div class="space-y-8">
          {#each project.webapp.screenshots as screenshot}
            <div>
              <img
                src={screenshot.url}
                alt={screenshot.caption}
                class="w-full h-auto shadow-2xl mb-4"
              />
              <p class="text-sm text-zinc-500 text-right">
                {screenshot.caption}
              </p>
            </div>
          {/each}
        </div>

        <!-- parte 2 -->
        <div class="max-w-6xl mx-auto bg-zinc-50 py-10 mt-10">
          <h2 class="text-2xl md:text-2xl font-light mb-8">
            {project.research.title}
          </h2>
          <p class="text-lg text-zinc-600 mb-16 max-w-4xl">
            {project.research.description}
          </p>

          <div class="grid md:grid-cols-3 gap-8">
            {#each project.research.findings as finding}
              <div class="bg-white p-8 border-l-4 border-zinc-900">
                <h3 class="text-lg font-medium mb-4 text-zinc-900">
                  {finding.insight}
                </h3>
                <p class="text-sm text-zinc-600 leading-relaxed">
                  {finding.description}
                </p>
              </div>
            {/each}
          </div>
        </div>

        <!-- Stack -->
        <div class="mt-16 pt-16 border-t border-zinc-200">
          <h3 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-6">
            Stack Técnico
          </h3>
          <div class="flex flex-wrap gap-3">
            {#each project.webapp.stack as tech}
              <span class="px-4 py-2 bg-zinc-900 text-white text-sm">
                {tech}
              </span>
            {/each}
          </div>
        </div>
        <div class="flex flex-wrap gap-12 text-sm pt-8">
          <div>
            <p class="text-zinc-500 uppercase tracking-wider mb-2">Duración</p>
            <p class="">{project.duration}</p>
          </div>
          {#each project.team as member}
            <div>
              <p class="text-zinc-500 uppercase tracking-wider mb-2">
                {member.role}
              </p>
              <p class="">{member.name}</p>
            </div>
          {/each}
        </div>
      </div>
    </div>
  </section>

  <!-- Separador con número -->
  <div class="border-t border-zinc-200 py-4">
    <div class="max-w-6xl mx-auto px-8 md:px-16">
      <span class="text-xs tracking-[0.3em] uppercase text-zinc-400"
        >03 de 03</span
      >
    </div>
  </div>

  <!-- DELIVERABLE 4: SOCIAL MEDIA -->
  <section class="py-32 px-8 md:px-16 bg-gradient-to-b from-white to-zinc-50">
    <div class="max-w-6xl mx-auto">
      <!-- Header -->
      <div class="mb-20">
        <div class="flex items-baseline gap-4 mb-6">
          <span class="text-7xl font-light text-zinc-200">03</span>
          <div>
            <h2 class="text-4xl md:text-5xl font-light mb-2 text-zinc-800">
              {project.social.title}
            </h2>
            <p class="text-xl text-zinc-500">{project.social.subtitle}</p>
          </div>
        </div>
        <p class="text-lg leading-relaxed text-zinc-600 max-w-3xl">
          {project.social.description}
        </p>
      </div>

      <!-- Galería de templates -->
      <div class="grid md:grid-cols-3 gap-6 mb-20">
        {#each project.social.gallery as template}
          <div class="group">
            <div class="overflow-hidden mb-4">
              <img
                src={template.url}
                alt={template.caption}
                class="w-full h-auto transition-transform group-hover:scale-105"
              />
            </div>
          </div>
        {/each}
      </div>

      <!-- Sistema de Diseño -->
      <section class="py-12 px-8 md:px-16 bg-zinc-900 text-white">
        <div class="max-w-6xl mx-auto">
          <h2 class="text-xl md:text-xl font-light mb-8 text-center">
            {project.designSystem.title}
          </h2>
          <p
            class="text-base text-zinc-300 leading-relaxed text-center mb-16 max-w-3xl mx-auto"
          >
            {project.designSystem.description}
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
            <span class="group-hover:-translate-x-1 transition-transform"
              >←</span
            >
            Volver a proyectos
          </a>
        </div>
      </section>
    </div>
  </section>
</article>
