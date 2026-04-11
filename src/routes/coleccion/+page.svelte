<script>
  import CardGaleria from '$lib/components/CardGaleria.svelte';
</script>

<section class="flex">
  <div class="flex flex-col m-auto mt-12 md:mt-20">
    <h3 class="text-5xl uppercase font-semibold text-center">Colección</h3>
    <p class="text-sm md:text-base text-center">
      Un recorrido por el proceso creativo
    </p>
  </div>
</section>
<section class="h-52 md:h-60 flex">
  <div class="flex flex-col pl-10 md:pl-16 mt-10 md:mt-20 w-11/12 md:w-1/2">
    <h3 class="text-xl uppercase font-semibold">Web & Producto</h3>
    <p class="text-sm md:text-base">
      Aquí se revela el trayecto invisible: Un recorrido por las ideas que se
      transforman en formas, colores y experiencias digitales, dando lugar a
      soluciones que habitan tanto lo estético como lo digital.
    </p>
  </div>
</section>
<section class="md:overflow-x-scroll md:pl-14 py-4">
  <ul class="flex flex-col md:flex-row gap-4 items-center">
    <li>
      <CardGaleria
        title="Endurance"
        image="/img-brand/endurance/portada.png"
        link="/coleccion/endurance"
      />
    </li>
    <li>
      <CardGaleria
        title="Suconsciencia"
        image="/img-brand/sucons/mokker-su.png"
        link="/coleccion/suconsciencia"
      />
    </li>
    <li>
      <CardGaleria
        title="Polyproto"
        image="/img-brand/poly/mokker.png"
        link="/coleccion/poly"
      />
    </li>
    <li>
      <CardGaleria
        title="weird"
        image="/img-brand/weird/portada.png"
        link="/coleccion/weird"
      />
    </li>
    <li>
      <CardGaleria
        title="roomy"
        image="/img-brand/roomy/portada.png"
        link="/coleccion/roomy"
      />
    </li>
  </ul>
</section>

<!-- galery -->
<section class="h-52 md:h-60 flex">
  <div class="flex flex-col pl-10 md:pl-16 mt-10 md:mt-20 w-11/12 md:w-1/2">
    <h3 class="text-xl uppercase font-semibold">Visual</h3>
    <p class="text-sm md:text-base">
      Cada pieza responde a una necesidad real, abordada desde un enfoque que
      busca coherencia, no hay piezas aisladas, sino un relato visual en
      constante movimiento.
    </p>
  </div>
</section>
<section class="md:overflow-x-scroll py-4">
  <ul class="flex flex-col md:flex-row gap-4 items-center justify-center">
    <li>
      <CardGaleria
        title="Colomba"
        image="/img-brand/colomba/col-procesos.png"
        link="/coleccion/colomba"
      />
    </li>
    <li>
      <CardGaleria
        title="Maica"
        image="/img-brand/maica/bolsa-maica.png"
        link="/coleccion/maica"
      />
    </li>
    <li>
      <CardGaleria
        title="Cerveceria del viento"
        image="/img-brand/delviento/portada-cdv.png"
        link="/coleccion/delviento"
      />
    </li>
    <li>
      <CardGaleria
        title="La casa de Anita"
        image="/img-brand/casanita/anita-port.jpg"
        link="/coleccion/casanita"
      />
    </li>
  </ul>
</section>
