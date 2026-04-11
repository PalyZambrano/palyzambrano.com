<script>
  const project = {
    title: 'Bitácora de pasos',
    category: 'Ilustración',
    year: '2026',
    description: [
      'Desde pequeña, mi relación con los zapatos no empezó como una elección, sino como una condición. Usé botines ortopédicos en una etapa que no recuerdo, pero que, de alguna forma, parece haber dejado una huella más profunda que cualquier memoria consciente. Hay algo en esa historia contada —más que vivida— que siento que me pertenece igual.',
      'Dicen que miraba los pies de la gente. No sus caras, no sus gestos, sino sus zapatos. Como si ahí hubiera algo que entender, algo que descifrar antes de saber siquiera cómo nombrarlo. Y cuando algo me gustaba, hacía un sonido simple, casi instintivo: “ooh”. Sin filtro, sin contexto. Solo una reacción pura ante la forma, el brillo, el movimiento.',
      'Quizás ahí empezó todo.',
      'Porque con el tiempo entendí que los zapatos no son solo objetos funcionales. Son decisiones. Son declaraciones silenciosas. Son una extensión de quién eres —o de quién estás intentando ser en ese momento.',
      'He tenido pares que marcaron etapas sin que me diera cuenta en ese instante. Zapatos que acompañaron versiones mías que hoy miro con distancia, con cariño, o incluso con extrañeza. Algunos quedaron intactos, como si no hubieran querido soltar esa versión de mí. Otros se desgastaron hasta perder su forma, como si hubieran absorbido cada paso, cada error, cada intento.',
      'Hay algo profundamente emocional en lo que elegimos para caminar.',
      'Porque al final, no recordamos todos los días. Pero sí recordamos cómo nos sentíamos en ciertos momentos. Y a veces, ese recuerdo vuelve a nosotros a través de algo tan simple como un par de zapatos.',
      'Tal vez por eso sigo mirando hacia abajo.',
      'Tal vez por eso sigo diciendo, en silencio o por dentro, “ooh”.'
    ],

    // Imágenes del proyecto (2-4 imágenes)
    images: [
      {
        url: 'https://images.unsplash.com/photo-1618005198919-d3d4b5a92ead?w=1200&q=80',
        caption: 'Vista principal del proyecto'
      },
      {
        url: 'https://images.unsplash.com/photo-1618556450994-a6a128ef0d9d?w=800&q=80',
        caption: 'Detalle de la implementación'
      },
      {
        url: 'https://images.unsplash.com/photo-1618556450991-2f1af64e8191?w=800&q=80',
        caption: 'Versión responsive'
      }
    ],

    // Highlights del proyecto (3-5 puntos)
    highlights: [
      'Diseño minimalista y funcional',
      'Desarrollo en tiempo récord',
      'Optimizado para móviles',
      'Integración con herramientas existentes'
    ],

    // Stack (opcional)
    stack: ['Figma', 'HTML/CSS', 'JavaScript', 'Tailwind'],

    // Links externos (opcional)
    links: [
      { text: 'Ver proyecto', url: '#' },
      { text: 'GitHub', url: '#' }
    ]
  };
</script>

<article class="min-h-screen bg-white">
  <!-- Hero Compacto -->
  <section class="px-6 md:px-12 pt-24 pb-16">
    <div class="max-w-4xl mx-auto">
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

  <!-- Grid de imágenes secundarias (si hay más de 1) -->
  {#if project.images.length > 1}
    <section class="px-6 md:px-12 py-16">
      <div class="max-w-5xl mx-auto">
        <div class="grid md:grid-cols-2 gap-8">
          {#each project.images.slice(1) as image}
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
</article>
