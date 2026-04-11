<script>
  const project = {
    title: 'La casa de Anita',
    subtitle: 'Un recuerdo dulce',
    year: '2025',
    type: 'Branding',
    curator: 'La casa de Anita',
    exhibition: 'Llay Llay, Valparaíso - Chile',
    description:
      'La Casa de Anita nace desde la memoria. Desde esos recuerdos simples que se quedan para siempre: una tarde de sol, una cuchara de helado derritiéndose lento y la sensación de estar en un lugar familiar. Inspirada en las antiguas gelaterías de barrio y en las recetas hechas en casa, la marca busca recuperar el valor de lo artesanal, lo cercano y lo auténtico. Más que una heladería, La Casa de Anita se plantea como un espacio donde cada sabor cuenta una historia y cada visita se siente como volver a casa.',
    statement:
      'La Casa de Anita posee una identidad flexible y con proyección, capaz de crecer junto a la marca y adaptarse a distintos soportes: packaging, vitrinas, redes sociales y espacios físicos. Su fuerte base narrativa permite construir una comunidad en torno a la experiencia, posicionándola como una heladería con historia, alma y tradición, preparada para perdurar en el tiempo.',

    challenge: {
      title: 'El Desafío',
      content:
        'El desafío fue transformar esa carga emocional en una identidad visual coherente y reconocible. ¿Cómo comunicar tradición sin verse obsoleto? ¿Cómo transmitir calidez, historia y cercanía en un contexto donde predominan las marcas modernas y estandarizadas? La marca necesitaba una identidad capaz de conectar desde la nostalgia, sin perder frescura ni relevancia en el presente.'
    },

    solution: {
      title: 'La Solución',
      content:
        'La solución fue construir un lenguaje visual inspirado en la estética de las gelaterías clásicas, con una mirada contemporánea. Se trabajó una identidad cálida y rústica, donde las tipografías con carácter, los colores suaves y los detalles artesanales refuerzan la idea de lo hecho con amor y tiempo.Cada elemento gráfico acompaña el relato de la marca, invitando a detenerse, disfrutar y reconectar con esos pequeños momentos que hacen especial lo cotidiano.'
    },

    process: [
      {
        phase: '01',
        title: 'Escuchar la historia',
        description:
          ' El punto de partida fue la historia detrás del nombre. La Casa de Anita nace como un homenaje a la abuela de la dueña, una figura ligada a los recuerdos, la cocina casera y los momentos compartidos. Comprender este origen fue clave para construir una marca auténtica, con alma y sentido.',
        image: '/img-brand/casanita/story.png'
      },
      {
        phase: '02',
        title: 'Traducir emociones en forma',
        description:
          'A partir de la investigación, se construyó el concepto central de la marca: una heladería con historia, cercana y acogedora. Se definieron sus valores, personalidad y tono, estableciendo una base clara que guiara todas las decisiones visuales y narrativas. El siguiente paso fue transformar esas emociones en un lenguaje visual. Se trabajó con referencias de gelaterías clásicas, tipografías con carácter, colores cálidos y elementos gráficos que evocan lo artesanal y lo hecho a mano.',
        image: '/img-brand/casanita/moodanita.png'
      },
      {
        phase: '03',
        title: 'El Color - Convertir recuerdos en identidad',
        description:
          'El tono frutilla evoca dulzura, calidez y cercanía. Remite a los helados preparados en casa, a las recetas heredadas y a los recuerdos de infancia ligados a la cocina de la abuela. Es un color emocional, amable y nostálgico, que refuerza la identidad familiar de la marca. El verde pistacho aporta equilibrio y frescura. Inspirado en ingredientes naturales y sabores tradicionales, transmite autenticidad, calidad y una conexión con lo artesanal. El Mantecado, su presencia suma sofisticación sin perder cercanía, reforzando el carácter clásico de la heladería.',
        image: '/img-brand/casanita/color-anita.png'
      },
      {
        phase: '04',
        title: 'Construir un sistema visual coherente',
        description:
          'Se desarrolló una identidad flexible y consistente, pensada para vivir en distintos soportes. Cada pieza —desde el logo hasta los detalles gráficos— fue diseñada para reforzar el relato de marca y generar una experiencia visual armoniosa y reconocible.',
        image: '/img-brand/casanita/logo-portafolio.png'
      },
      {
        phase: '05',
        title: 'Conectar con la comunidad',
        description:
          'Las redes sociales de La Casa de Anita se conciben como una extensión de la experiencia de la heladería: un espacio cálido y cercano donde la marca comparte su historia, sus sabores y los pequeños momentos que la definen.',
        image: '/img-brand/casanita/redes.png'
      }
    ],

    testimonial: {
      quote:
        'Desde el inicio sentimos que se entendió perfecto lo que queríamos transmitir con La Casa de Anita. La historia de mi abuela era muy importante para mí y se trasladó a la identidad de la marca con mucho cariño. Hoy la heladería se siente cálida, familiar y muy nuestra. Cada detalle refleja el amor con el que hacemos nuestros helados.”',
      author: 'Michelle',
      role: 'Founder, Gelateria La Casa de Anita'
    },

    images: [
      {
        url: '/img-brand/casanita/cartel.png',
        caption: 'portada'
      },
      {
        url: '/img-brand/test.jpg',
        caption: 'Cartel'
      },
      {
        url: '/img-brand/casanita/vasitos.png',
        caption: 'Vasos de café'
      }
    ],
    brandAssets: [
      { url: '/img-brand/casanita/vasitos.png', caption: 'Logo principal' },
      { url: '/img-brand/casanita/box-anita.png', caption: 'Tipografía' },
      { url: '/img-brand/casanita/manija-anita.png', caption: 'Tipografía' },
      {
        url: '/img-brand/casanita/bolsas-anita.png',
        caption: 'diseño de bolsas'
      }
    ],

    nextProject: {
      title: 'Próximo Proyecto',
      name: 'Siguiente proyecto',
      link: '#'
    }
  };
</script>

<article class="min-h-screen bg-white">
  <!-- Hero: Título a la izquierda, Info a la derecha -->
  <section class="min-h-screen grid md:grid-cols-2">
    <!-- Columna izquierda: Título -->
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
      <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-8">
        Proyección
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
          <img
            src={step.image}
            alt={step.title}
            class="px-8 md:px-16 w-full object-cover mb-8"
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
              class="w-full object-cover"
            />
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

  <!-- Testimonial: Layout dividido -->
  <section class="grid md:grid-cols-2 min-h-[60vh]">
    <div class="bg-[#a9a75c] p-16 md:p-24 flex items-center justify-center">
      <video
        src="/img-brand/casanita/video-anita.mp4"
        autoplay
        loop
        poster="posterimage.jpg"
      />
    </div>
    <div class="p-16 md:p-24 flex flex-col justify-center">
      <blockquote
        class="text-xl md:text-2xl font-light leading-relaxed mb-8 text-zinc-700"
      >
        "{project.testimonial.quote}"
      </blockquote>
      <div>
        <p class="text-base font-medium text-zinc-900">
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
