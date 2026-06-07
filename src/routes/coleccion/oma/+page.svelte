<script>
  const project = {
    title: 'OMA',
    category: 'Papelería',
    year: '2024',
    description:
      'Este es un proyecto más pequeño que no requiere tanta narrativa. Perfecto para trabajos rápidos, experimentos, o proyectos personales que quieres mostrar de forma concisa y directa.',

    // Info básica
    info: [
      { label: 'Cliente', value: 'Nombre del Cliente' },
      { label: 'Duración', value: '2 semanas' },
      { label: 'Rol', value: 'Diseño y Desarrollo' }
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

  <!-- Imagen principal grande -->
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

  <!-- Highlights + Stack en dos columnas -->
  <section class="px-6 md:px-12 py-16 bg-zinc-50">
    <div class="max-w-5xl mx-auto grid md:grid-cols-2 gap-12">
      <!-- Highlights -->
      <div>
        <h2 class="text-xs tracking-[0.3em] uppercase text-zinc-400 mb-6">
          Highlights
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

  <!-- Links externos (si hay) -->
  {#if project.links && project.links.length > 0}
    <section class="px-6 md:px-12 py-16 border-t border-zinc-200">
      <div class="max-w-5xl mx-auto flex flex-wrap gap-4">
        {#each project.links as link}
          <a
            href={link.url}
            target="_blank"
            rel="noopener noreferrer"
            class="inline-block border border-zinc-300 px-6 py-3 text-xs tracking-[0.2em] uppercase hover:bg-zinc-900 hover:text-white hover:border-zinc-900 transition-colors"
          >
            {link.text} →
          </a>
        {/each}
      </div>
    </section>
  {/if}

  <!-- Footer simple -->
  <section class="px-6 md:px-12 py-16 bg-zinc-50">
    <div class="max-w-5xl mx-auto">
      <a
        href="#"
        class="group inline-flex items-center gap-3 text-sm text-zinc-500 hover:text-zinc-900 transition-colors"
      >
        <span class="group-hover:-translate-x-1 transition-transform">←</span>
        Volver a proyectos
      </a>
    </div>
  </section>
</article>
