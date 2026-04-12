<script>
  // Props del componente
  export let title;
  export let image;
  export let link;
</script>

<a href={link} class="block group">
  <article
    class="md:w-96 w-80 h-96 grayscale bg-cover bg-center transition-all duration-300"
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
