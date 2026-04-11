<script>
  const project = {
    title: 'MAICA',
    subtitle: 'El hogar de tu esencia',
    year: '2025',
    type: 'Branding',
    curator: 'Carla',
    exhibition: 'Llay Llay, Valparaíso - Chile',
    description:
      'Maica es una marca de accesorios femeninos que nace con el propósito de convertirse en un espacio donde la elegancia, la feminidad y el carácter se encuentran. Su concepto parte de una idea poderosa: “como si el armario de Blair Waldorf fuera una tienda”. Desde ahí, Maica se construye como una experiencia de estilo curado, que combina diseño propio con piezas seleccionadas, logrando un universo único de sofisticación accesible.',
    statement:
      'Maica se diferencia al ofrecer no solo productos, sino una curaduría aspiracional: cada pieza está pensada como parte de un armario soñado, donde todo dialoga bajo un mismo lenguaje de estilo. Esta coherencia permite proyectar a la marca como un referente de lujo accesible, capaz de trascender modas pasajeras y consolidarse como un símbolo de feminidad auténtica.',

    challenge: {
      title: 'El Desafío',
      content:
        'El reto creativo era definir una marca que no se limitara a vender accesorios, sino que transmitiera un estilo de vida aspiracional. El objetivo fue diseñar una identidad que reflejara lujo, distinción y autenticidad, pero con un lenguaje cercano que permitiera conectar con mujeres reales que buscan expresarse a través de los detalles '
    },

    solution: {
      title: 'La Solución',
      content:
        'El desarrollo de Maica se basa en la creación de una marca integral, pensada para resonar emocionalmente con las mujeres que buscan expresarse a través de su estilo personal. Para ello, se tomó un enfoque estratégico que integró tanto el diseño como la narrativa visual y conceptual de la marca.',
      highlights: [
        'Eslogan: “El hogar de tu esencia” no es solo una frase, es la promesa de que en Maica cada cliente puede encontrar aquello que le represente.',
        'Identidad visual: Estilo sofisticado, femenino y versátil, con una estética que equilibra lo aspiracional con lo cercano.',
        'Narrativa de marca: Un relato que convierte a cada accesorio en un símbolo de distinción y carácter.'
      ]
    },

    process: [
      {
        phase: '01',
        title: 'Investigación y Moodboard',
        description:
          'El proceso comenzó con una fase de exploración visual y conceptual donde se analizaron referentes del mundo de la moda, el lujo accesible y marcas con estética femenina y sofisticada. Se revisaron elementos inspirados en la idea de un armario icónico —elegante, curado y con fuerte identidad— así como detalles estéticos que aportan una dirección clara: feminidad, distinción y carácter.',
        image: '/img-brand/maica/maica-celeste.jpg'
      },
      {
        phase: '02',
        title: 'Bocetaje y exploración tipográfica',
        description:
          'La etapa creativa inició con una amplia exploración tipográfica y bocetaje, donde se desarrollaron distintas propuestas basadas en serif y semi-serif elegantes que transmitieran feminidad y distinción. Se experimentó con variaciones de peso, serifas personalizadas y terminaciones suaves para encontrar una estructura que representara el carácter de Maica. Una vez seleccionada la tipografía más adecuada, se procedió a un proceso minucioso de refinamiento, ajustando espaciados, curvas, proporciones y ritmo visual entre letras. Este trabajo detallado permitió construir un logotipo equilibrado, sofisticado y coherente con los pilares visuales de la marca.',
        image: '/img-brand/maica/boceto-maica.png'
      },
      {
        phase: '03',
        title: 'Paleta de Color',
        description:
          'Se incorporaron tonos celestes para transmitir frescura, calma y una elegancia sutil que refleja la esencia de Maica. El celeste es versátil y accesible para un público amplio, aportando modernidad y una estética atemporal. Además, conecta con el concepto “El hogar de tu esencia”, ya que evoca tranquilidad y confianza. Su combinación con otros tonos —como beige o azul— permite añadir un toque de exclusividad y equilibrio a la identidad visual.',
        image: '/img-brand/maica/paleta-maica.png'
      }
    ],

    technologies: {
      title: 'Herramientas',
      stack: [
        { category: 'Diseño', items: ['Adobe Illustrator', 'Photoshop'] },
        {
          category: 'Aplicaciones',
          items: ['Papelería']
        },
        { category: 'Elementos', items: ['Logotipo', 'Packaging'] },
        {
          category: 'Implementación',
          items: ['Identidad Visual']
        }
      ]
    },

    testimonial: {
      quote:
        'El resultado superó completamente mis expectativas. El proyecto no solo es hermoso, sino que transmite exactamente lo que quería para mi marca. Estoy profundamente agradecida',
      author: 'Carla',
      role: 'Founder, Maica'
    },

    images: [
      {
        url: '/img-brand/maica/portada-maica.png',
        caption: 'Maica'
      },
      {
        url: '/img-brand/maica/bolsa-maica.png',
        caption: 'Línea de papelería navideña y vitrina temática'
      },
      {
        url: '/img-brand/maica/stick-maica.png',
        caption: 'Implementación de vitrina con nueva identidad'
      },
      {
        url: '/img-brand/maica/box-maica.png',
        caption: 'Implementación de vitrina con nueva identidad'
      }
    ],

    brandAssets: [
      { url: '/img-brand/maica/etiqueta-maica.png', caption: 'etiquetas' },
      {
        url: '/img-brand/maica/fotos-maica.png',
        caption: 'Cinta cierra cajas'
      },
      {
        url: '/img-brand/maica/redes-maica.png',
        caption: 'Tarjeta agradecimientos'
      }
    ],

    nextProject: {
      title: 'Próximo Proyecto',
      name: 'Siguiente proyecto',
      link: '/galeria/delviento'
    }
  };
</script>

<article class="min-h-screen bg-white">
  <!-- Hero -->
  <section class="min-h-screen grid md:grid-cols-2">
    <!-- Columna izquierda: Imagen principal -->
    <div class="relative h-screen">
      <img
        src={project.images[0].url}
        alt={project.title}
        class="w-full h-full object-cover object-top"
      />
    </div>
    <!-- Columna derecha: Título -->
    <div class="flex flex-col justify-center px-8 md:px-16 py-24 md:py-0">
      <span class="text-xs tracking-[0.4em] uppercase text-zinc-400 mb-8">
        {project.type}
      </span>
      <h1
        class="text-7xl md:text-8xl font-light tracking-tight leading-none mb-8"
      >
        {project.title}
      </h1>
      <p class="text-xl text-zinc-600 leading-relaxed mb-12">
        {project.subtitle}
      </p>

      <div class="space-y-4 text-sm">
        <div class="flex gap-4">
          <span class="text-zinc-400 w-24">Cliente</span>
          <span class="text-zinc-800">{project.curator}</span>
        </div>
        <div class="flex gap-4">
          <span class="text-zinc-400 w-24">Ubicación</span>
          <span class="text-zinc-800">{project.exhibition}</span>
        </div>
        <div class="flex gap-4">
          <span class="text-zinc-400 w-24">Año</span>
          <span class="text-zinc-800">{project.year}</span>
        </div>
      </div>
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
  <section class="grid md:grid-cols-3 gap-px bg-zinc-200 mt-14">
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
    <div class="bg-white p-12 md:p-16 md:col-span-2">
      <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-8">
        {project.solution.title}
      </h2>
      <p class="text-base leading-relaxed text-zinc-700 mb-12">
        {project.solution.content}
      </p>

      <div class="grid md:grid-cols-2 gap-6">
        {#each project.solution.highlights as highlight}
          <div class="border-t border-zinc-300 pt-4">
            <p class="text-sm text-zinc-600">{highlight}</p>
          </div>
        {/each}
      </div>
    </div>
  </section>

  <!-- Statement con borde lateral -->
  <section class="py-24 px-8 md:px-16 bg-zinc-50">
    <div class="max-w-4xl border-l-4 border-zinc-300 pl-8">
      <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-8">
        El potencial icónico
      </h2>
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
        <!-- Layout: Imagen full width arriba, texto abajo en dos columnas -->
        <div class="mb-12">
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
          <img
            src={step.image}
            alt={step.title}
            class="px-8 md:px-40 w-full object-cover mb-8"
          />
        </div>
      {:else}
        <!-- Layout: Texto a la izquierda, imagen a la derecha -->
        <div class="px-8 md:px-16 mb-32">
          <div class="grid md:grid-cols-2 gap-16 items-center">
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
              class="w-full h-[600px] object-cover"
            />
          </div>
        </div>
      {/if}
    {/each}
  </section>

  <!-- Implementaciones: Grid irregular -->
  <section class="pb-32 px-8 md:px-16">
    <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-16">
      Implementaciones
    </h2>

    <div class="grid md:grid-cols-6 gap-4">
      <!-- Imagen grande -->
      <div class="md:col-span-3 md:row-span-2">
        <img
          src={project.images[1].url}
          alt={project.images[1].caption}
          class="w-full h-full object-cover"
        />
      </div>

      <!-- Dos imágenes pequeñas -->
      <div class="md:col-span-3">
        <img
          src={project.images[2].url}
          alt={project.images[2].caption}
          class="w-full h-full object-cover"
        />
      </div>
      <div class="md:col-span-3">
        <img
          src={project.images[3].url}
          alt={project.images[3].caption}
          class="w-full h-full object-cover"
        />
      </div>
    </div>

    <!-- Sistema de identidad: Grid tipo Pinterest -->
    <section class="mt-4 pb-20">
      <div class="columns-1 md:columns-2 lg:columns-3 gap-4">
        {#each project.brandAssets as asset}
          <div class="break-inside-avoid">
            <img src={asset.url} alt={asset.caption} class="w-full mb-4" />
          </div>
        {/each}
      </div>
    </section>
  </section>

  <!-- Stack: Horizontal en una línea -->
  <section class="border-y border-zinc-200 py-16 px-8 md:px-16 overflow-x-auto">
    <div class="px-6 md:px-16 flex gap-16 min-w-max">
      {#each project.technologies.stack as tech}
        <div class="min-w-[200px]">
          <h3 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-6">
            {tech.category}
          </h3>
          <ul class="space-y-2">
            {#each tech.items as item}
              <li class="text-sm text-zinc-700">{item}</li>
            {/each}
          </ul>
        </div>
      {/each}
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
