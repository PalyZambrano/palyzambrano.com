<!--<a href="/">
  <h4 class="uppercase">Colomba</h4>
  <article
    class="w-80 h-[400px] grayscale hover:grayscale-0 bg-[url(/procesos/colomba/col-procesos.png)] bg-cover flex justify-center items-center"
  >
    <div
      class="text-white text-center w-full h-full bg-zinc-900/40 flex flex-col justify-center items-center"
    />
  </article>
</a>-->
<!-- new -->

<script>
  // Props del componente
  export let title;
  export let image;
  export let link;
</script>

<a href={link} class="block group">
  <article
    class="w-96 h-80 grayscale bg-cover bg-center transition-all duration-300"
    style="background-image: url({image})"
  >
    <div
      class="w-full h-full bg-zinc-900/80 flex flex-col justify-center items-center transition-all duration-300"
    >
      <div class="text-white text-center px-6">
        <span>*</span>
        <h4 class="uppercase text-2xl font-light tracking-wider mb-2">
          {title}
        </h4>
      </div>
    </div>
  </article>
</a>
