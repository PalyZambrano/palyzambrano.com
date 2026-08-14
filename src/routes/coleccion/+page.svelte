<script>
  import HorizontalGallery from '$lib/components/HorizontalGallery.svelte';

  const webProjects = [
    { title: 'Endurance', image: '/img-brand/endurance/portada.png', link: '/coleccion/endurance' },
    { title: 'Suconsciencia', image: '/img-brand/sucons/mokker-su.png', link: '/coleccion/suconsciencia' },
    { title: 'Polyproto', image: '/img-brand/poly/mokker.png', link: '/coleccion/poly' },
    { title: 'Weird', image: '/img-brand/weird/portada.png', link: '/coleccion/weird' },
    { title: 'Roomy', image: '/img-brand/roomy/portada.png', link: '/coleccion/roomy' }
  ];

  const visualProjects = [
    { title: 'Colomba', image: '/img-brand/colomba/col-procesos.png', link: '/coleccion/colomba' },
    { title: 'Maica', image: '/img-brand/maica/bolsa-maica.png', link: '/coleccion/maica' },
    { title: 'Cerveceria del viento', image: '/img-brand/delviento/portada-cdv.png', link: '/coleccion/delviento' },
    { title: 'La casa de Anita', image: '/img-brand/casanita/anita-port.jpg', link: '/coleccion/casanita' }
  ];
</script>

<section class="flex">
  <div class="flex flex-col m-auto mt-12 md:mt-20">
    <h3 class="text-5xl uppercase font-semibold text-center">Colección</h3>
    <p class="text-sm md:text-base text-center">
      Un recorrido por el proceso creativo
    </p>
  </div>
</section>
<HorizontalGallery
  title="Web & Producto"
  description="Aquí se revela el trayecto invisible: Un recorrido por las ideas que se transforman en formas, colores y experiencias digitales, dando lugar a soluciones que habitan tanto lo estético como lo digital."
  projects={webProjects}
/>

<!-- galery -->
<HorizontalGallery
  title="Visual"
  description="Cada pieza responde a una necesidad real, abordada desde un enfoque que busca coherencia, no hay piezas aisladas, sino un relato visual en constante movimiento."
  projects={visualProjects}
/>
