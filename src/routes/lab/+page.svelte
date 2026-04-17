<script>
  import CardLab from '$lib/components/CardLab.svelte';
</script>

<main class="flex flex-col md:flex-row justify-between md:px-16 py-20">
  <section class="w-full md:w-2/6">
    <article class="md:fixed w-full px-12 md:px-0 md:w-4/12">
      <div class="flex flex-col">
        <h3 class="text-5xl uppercase font-semibold">Lab</h3>
        <span class="pt-2 pb-4">Este es un espacio de exploración. </span>
        <p class="text-sm md:text-base pb-3 md:pr-10">
          Un lugar donde las ideas toman forma sin una estructura fija: pruebo,
          mezclo y experimento entre diseño, arte y materia.
        </p>
        <p class="text-sm md:text-base md:pr-10 pb-12">
          Desde el desarrollo y confección de prendas hasta ejercicios visuales
          y procesos abiertos, cada proyecto es parte de una búsqueda constante
          por entender cómo crear desde la intuición, el juego y la curiosidad.
        </p>
      </div>
    </article>
  </section>
  <section class="w-ful md:w-4/6">
    <!-- <section class="w-3/4 md:w-2/5 md:h-96 md:overflow-y-scroll "> -->
    <ul class="flex flex-wrap gap-3 md:justify-end justify-center">
      <li>
        <CardLab
          title="Bitácora de pasos"
          image="/img-lab/zapas/zuecos.JPG"
          link="/lab/zapas"
        />
      </li>
      <li>
        <CardLab
          title="Boda N&D"
          image="/img-lab/bodand.png"
          link="/lab/bodand"
        />
      </li>
      <li>
        <CardLab
          title="BAFOTCH"
          image="/img-lab/bafotch.png"
          link="/lab/bafotch"
        />
      </li>
      <li>
        <CardLab
          title="Maica"
          image="/img-brand/maica/bolsa-maica.png"
          link="/galeria/maica"
        />
      </li>
      <li>
        <CardLab
          title="Colomba"
          image="/img-brand/colomba/col-procesos.png"
          link="/galeria/colomba"
        />
      </li>
      <li>
        <CardLab
          title="Maica"
          image="/img-brand/maica/bolsa-maica.png"
          link="/galeria/maica"
        />
      </li>
    </ul>
  </section>
</main>
