<script>
  export let coverImage = '';
  export let coverAlt = '';
  export let text = '';
  export let appleUrl = '';
  let playing = false;
  let progress = 0;

</script>

<section class="w-full border border-1 border-black p-4">
  {#if coverImage}
    <img
      src={coverImage}
      alt={coverAlt}
      class="w-full object-contain  rounded-xl mb-6"
    />
  {/if}
  <div class="w-full h-36 ">
    <iframe
      allow="autoplay *; 
      encrypted-media *;"
      frameborder="0"
      height="150"
      style="width:100%;max-width:660px;overflow:hidden;background:transparent;"
      sandbox="allow-forms allow-popups allow-same-origin allow-scripts allow-storage-access-by-user-activation allow-top-navigation-by-user-activation"
      src={appleUrl}
    />
  </div>
  {#if text}
    <p class="text-base text-zinc-600 leading-relaxed mb-6 pt-6">{text}</p>
  {/if}
</section>
