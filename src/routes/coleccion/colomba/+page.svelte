<script>
  const project = {
    title: 'COLOMBA',
    subtitle: 'Rebranding de Pastelería Artesanal',
    year: '2024',
    type: 'Rebranding',
    curator: 'Pastelería Colomba',
    exhibition: 'Llay Llay , valparaíso - Chile',
    description:
      'Pastelería Colomba es una marca dedicada a la repostería artesanal, donde cada postre es una obra cuidada en sabor y presentación. El objetivo de este proyecto fue desarrollar una identidad visual elegante y atemporal que transmita la calidad, dedicación y estilo único de sus creaciones, posicionando a Colomba como un referente en pastelería de alto nivel.',
    statement:
      'La marca llevaba muchos años utilizando como su logo el dibujo de una batidora. La clienta amaba su batidora porque era la imagen que la había acompañado desde que comenzó haciendo tortas en la casa de sus papás, pero también entendía que era momento de soltar. Su negocio estaba creciendo y la imagen que la había acompañado tanto tiempo se estaba convirtiendo en un problema.',

    challenge: {
      title: 'El Desafío',
      content:
        'La pastelería no solo es un espacio donde se va por algo rico, también imparten talleres y cursos de cocina para niños y adultos. Necesitábamos crear una identidad que reflejara esta evolución, manteniendo la calidez artesanal pero proyectando profesionalismo y elegancia.'
    },

    solution: {
      title: 'La Solución',
      content:
        'Junto a Constanza, dueña de esta pastelería, creamos un moodboard en colaboración con sus referencias y aterrizamos todas esas ideas que vivían en nuestra imaginación. La identidad de Colomba ya existía conceptualmente, pero había que hacerlo tangible.',
      highlights: [
        "Cambio de nombre: Colomba's Cake → Colomba",
        'Logotipo con rosca juguetona en la C',
        'Paleta de colores definida con rosas elegantes',
        'Sistema de patrones para papel manteca',
        'Implementación completa en local renovado'
      ]
    },

    process: [
      {
        phase: '01',
        title: 'Investigación y Moodboard',
        description:
          'Comenzamos con reuniones para entender qué se esperaba de la nueva identidad. Creamos un moodboard colaborativo con referencias que aterrizaran todas las ideas que vivían en nuestra imaginación.',
        image: '/img-brand/colomba/moodcolomba.png'
      },
      {
        phase: '02',
        title: 'Definición de Nombre',
        description:
          "Colomba's Cake se transformó en Colomba, porque era la forma en que todos los clientes la llamaban. 'Pasemos donde Colomba', 'esas tortas las consigues en Colomba'. Era la forma como los clientes habían adoptado la marca naturalmente.",
        image: '/img-brand/colomba/antesco.png'
      },
      {
        phase: '03',
        title: 'Diseño del Logotipo',
        description:
          'Buscábamos algo clásico y al mismo tiempo elegante, atemporal, que transmitiera la calidez y la calidad artesanal. Bocetamos varios diseños buscando la tipografía perfecta que representara la marca.',
        image: '/img-brand/colomba/propuesta1.png'
      },
      {
        phase: '04',
        title: 'Refinamiento - La Rosca',
        description:
          'Algo faltaba en la primera versión. Revisando el moodboard, noté el Golden Ticket de Willy Wonka con ese firulete juguetón. Agregué una rosca en la letra C que resaltó esa esencia creativa y fresca. El logo dice: soy elegante pero también divertido.',
        image: '/img-brand/colomba/propuesta2.png'
      },
      {
        phase: '05',
        title: 'Paleta de Color',
        description:
          'Colomba había ganado un financiamiento para remodelar su pastelería. Seleccionamos los colores cuidadosamente para aplicarlos en las paredes del local. El rosa había acompañado a la marca muchas veces, pero teníamos que definir cuál era el tono correcto.',
        image: '/img-brand/colomba/colpaleta.png'
      }
    ],

    technologies: {
      title: 'Herramientas',
      stack: [
        { category: 'Diseño', items: ['Adobe Illustrator', 'Photoshop'] },
        {
          category: 'Aplicaciones',
          items: ['Papelería', 'Uniformes', 'Señalética']
        },
        { category: 'Elementos', items: ['Logotipo', 'Patrones', 'Packaging'] },
        {
          category: 'Implementación',
          items: ['Remodelación de Local', 'Vitrina', 'Identidad Visual']
        }
      ]
    },

    testimonial: {
      quote:
        'La nueva identidad capturó perfectamente la evolución de Colomba. Pasamos de una imagen casera a una marca profesional que refleja la calidad de nuestros productos y la experiencia que ofrecemos en talleres y cursos.',
      author: 'Constanza',
      role: 'Founder, Pastelería Colomba'
    },

    images: [
      {
        url: '/img-brand/colomba/col-procesos.png',
        caption: 'Fachada de pastelería Colomba'
      },
      {
        url: '/img-brand/colomba/navidad.png',
        caption: 'Línea de papelería navideña y vitrina temática'
      },
      {
        url: '/img-brand/colomba/vitrina.png',
        caption: 'Implementación de vitrina con nueva identidad'
      }
    ],

    nextProject: {
      title: 'Próximo Proyecto',
      name: 'Siguiente proyecto',
      link: '/galeria/maica'
    },

    instagramLinks: [
      {
        text: 'Ver video de vitrina en Instagram',
        url: 'https://www.instagram.com/reels/DDX0tVzPAOQLNNABjkuPVJN3ZwfNYssPPzHcy40/'
      }
    ],
    brandAssets: [
      { url: '/img-brand/colomba/coluno.png', caption: 'Logo principal' },
      { url: '/img-brand/colomba/coltres.png', caption: 'Tipografía' },
      {
        url: '/img-brand/colomba/colcuatro.png',
        caption: 'Tarjetas de presentación'
      },
      { url: '/img-brand/colomba/colcinco.png', caption: 'Patrón de papel' },
      { url: '/img-brand/colomba/cinta.png', caption: 'Cinta cierra cajas' },
      {
        url: '/img-brand/colomba/colseis.png',
        caption: 'Tarjeta agradecimientos'
      }
    ]
  };
</script>

<article class="min-h-screen bg-white">
  <!-- Hero minimalista con mucho espacio en blanco -->
  <section class="px-6 md:px-16 pt-32 pb-14">
    <div class="max-w-6xl mx-auto">
      <div class="mb-16">
        <p class="text-sm tracking-[0.4em] uppercase text-zinc-400 mb-12">
          {project.type} · {project.year}
        </p>
        <h1
          class="text-6xl md:text-8xl font-light tracking-tight mb-2 leading-none"
        >
          {project.title}
        </h1>
        <p class="md:col-span-5 text-lg text-zinc-600 leading-relaxed">
          {project.subtitle}
        </p>
      </div>

      <div class="grid md:grid-cols-12 gap-12">
        <div
          class="md:col-span-6 md:col-start-7 space-y-4 text-sm text-zinc-500"
        >
          <div class="flex">
            <span class="w-32 uppercase tracking-wider">Cliente</span>
            <span class="text-zinc-800 pl-4">{project.curator}</span>
          </div>
          <div class="flex">
            <span class="w-32 uppercase tracking-wider">Ubicación</span>
            <span class="text-zinc-800 pl-4">{project.exhibition}</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Imagen principal con caption -->
  <section class="mb-24">
    <img
      src={project.images[0].url}
      alt={project.images[0].caption}
      class="w-full h-[80vh] object-cover object-top"
    />
    <div class="px-6 md:px-16 pt-4">
      <p class="text-xs text-zinc-400 max-w-6xl mx-auto">
        {project.images[0].caption}
      </p>
    </div>
  </section>

  <!-- Descripción y statement -->
  <section class="px-6 md:px-16 pb-24">
    <div class="max-w-6xl mx-auto grid md:grid-cols-12 gap-16">
      <div class="md:col-span-5">
        <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-6">
          Contexto
        </h2>
        <p class="text-base leading-relaxed text-zinc-700">
          {project.description}
        </p>
      </div>

      <div class="md:col-span-6 md:col-start-7 bg-zinc-50 p-8">
        <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-6">
          El Punto de Partida
        </h2>
        <p class="text-base leading-relaxed text-zinc-700 italic">
          {project.statement}
        </p>
      </div>
    </div>
  </section>

  <!-- Desafío -->
  <section class="px-6 md:px-16 pb-24">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-12">
        {project.challenge.title}
      </h2>
      <p
        class="text-xl md:text-xl font-light leading-relaxed text-zinc-800 max-w-4xl"
      >
        {project.challenge.content}
      </p>
    </div>
  </section>

  <!-- Solución con highlights -->
  <section class="px-6 md:px-16 pb-24 bg-zinc-50 py-24">
    <div class="max-w-6xl mx-auto grid md:grid-cols-12 gap-16">
      <div class="md:col-span-7">
        <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-6">
          {project.solution.title}
        </h2>
        <p class="text-lg leading-relaxed text-zinc-700 mb-8">
          {project.solution.content}
        </p>
      </div>

      <div class="md:col-span-4 md:col-start-9">
        <h3 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-6">
          Elementos Clave
        </h3>
        <ul class="space-y-3">
          {#each project.solution.highlights as highlight}
            <li class="text-sm text-zinc-600 flex items-start">
              <span class="text-zinc-400 mr-3">—</span>
              {highlight}
            </li>
          {/each}
        </ul>
      </div>
    </div>
  </section>

  <!-- Proceso con imágenes -->
  <section class="px-6 md:px-16 pb-24 pt-24">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-16">
        Proceso
      </h2>
      <div class="space-y-24">
        {#each project.process as step, i}
          <div class="grid md:grid-cols-12 gap-12 items-center">
            <div class="md:col-span-6">
              <span class="text-6xl font-light text-zinc-300 block mb-4"
                >{step.phase}</span
              >
              <h3 class="text-3xl font-light mb-6 text-zinc-800">
                {step.title}
              </h3>
              <p class="text-base text-zinc-600 leading-relaxed">
                {step.description}
              </p>
            </div>
            <div class="md:col-span-6">
              <img
                src={step.image}
                alt={step.title}
                class="w-full h-full object-cover"
              />
            </div>
          </div>
        {/each}
      </div>
    </div>
  </section>

  <!-- Sistema de Identidad - Grid masonry -->
  <section class="bg-white text-zinc-900 py-32">
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

  <!-- Grid de imágenes secundarias -->
  <section class="px-6 md:px-16 pb-24 bg-zinc-50 py-24">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-12">
        Implementaciónes
      </h2>
      <div class="grid md:grid-cols-2 gap-8 mb-12">
        {#each project.images.slice(1) as image}
          <div>
            <img
              src={image.url}
              alt={image.caption}
              class="w-full object-cover mb-4"
            />
            <p class="text-xs text-zinc-400">{image.caption}</p>
          </div>
        {/each}
      </div>

      <!-- Links Relacionados -->
      <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-12">
        Links Relacionados
      </h2>
      <div class="flex flex-col md:flex-row gap-4 mt-8">
        {#each project.instagramLinks as link}
          <a
            href={link.url}
            target="_blank"
            rel="noopener noreferrer"
            class="inline-block border border-zinc-300 px-6 py-3 text-xs tracking-[0.2em] uppercase hover:bg-zinc-900 hover:text-white hover:border-zinc-900 transition-colors duration-300"
          >
            {link.text} →
          </a>
        {/each}
      </div>
    </div>
  </section>

  <!-- Stack Tecnológico -->
  <section class="px-6 md:px-16 pb-24 text-white py-24">
    <div class="max-w-6xl mx-auto px-6 md:px-16 py-14 bg-zinc-50">
      <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-12">
        {#each project.technologies.stack as tech}
          <div>
            <h3 class="text-xs tracking-[0.3em] uppercase text-zinc-500 mb-6">
              {tech.category}
            </h3>
            <ul class="space-y-3">
              {#each tech.items as item}
                <li class="text-base text-zinc-700">{item}</li>
              {/each}
            </ul>
          </div>
        {/each}
      </div>
    </div>
  </section>

  <!-- Testimonial -->
  <section class="px-6 md:px-16 pb-24 pt-24">
    <div class="max-w-4xl mx-auto text-center">
      <blockquote class="mb-8">
        <p
          class="text-lg md:text-xl font-light italic leading-relaxed text-zinc-700 mb-8"
        >
          "{project.testimonial.quote}"
        </p>
      </blockquote>
      <div>
        <p class="text-base font-medium text-zinc-800">
          {project.testimonial.author}
        </p>
        <p class="text-sm text-zinc-500">{project.testimonial.role}</p>
      </div>
    </div>
  </section>

  <!-- Próximo Proyecto -->
  <section class="px-6 md:px-16 pb-32 pt-16 border-t border-zinc-200">
    <div class="max-w-6xl mx-auto">
      <a href={project.nextProject.link} class="group block">
        <p class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-4">
          {project.nextProject.title}
        </p>
        <div class="flex items-center justify-between">
          <h3
            class="text-xl md:text-2xl font-light text-zinc-800 group-hover:text-zinc-600 transition-colors"
          >
            {project.nextProject.name}
          </h3>
          <span
            class="text-3xl text-zinc-400 group-hover:translate-x-2 transition-transform"
            >→</span
          >
        </div>
      </a>
    </div>
  </section>
</article>
