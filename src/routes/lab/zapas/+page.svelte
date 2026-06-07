<script>
  import SongCard from '$lib/components/SongCard.svelte';

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
        class="text-5xl md:text-7xl font-light tracking-tight mb-8 leading-tight">
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
  <section class="px-6 md:px-12 py-16">
    <div class="max-w-7xl mx-auto">
      <div class="grid md:grid-cols-2 gap-8">
        <SongCard
          coverImage="/img-lab/zapas/zuecos.JPG"
          coverAlt="Zuecos"
          text="Los zuecos de mi abuela nunca fueron realmente suyos, al menos no en el recuerdo. Permanecían quietos, como esperando, mientras yo intentaba entenderlos. Me fascinaban por su peso y por ese sonido seco contra el suelo, casi como un pequeño eco con cada paso torpe. No lograba comprender cómo podían sostenerse en los pies sin abrazar el talón; a mí se me escapaban, obligándome a arrastrarlos más que a caminar. En esa casa, entre el ritmo constante de los boleros y los abrazos de mi abuelo convertidos en baile, esos zuecos eran menos un objeto y más un misterio: una forma temprana de descubrir que no todo lo que nos llama está hecho para ser entendido de inmediato."
          appleUrl="https://embed.music.apple.com/es/album/que-nadie-sepa-mi-sufrir/1834214811?i=1834214971"
        />
        <SongCard
          coverImage="/img-lab/zapas/charol.JPG"
          coverAlt="Zapatos de Charol"
          text="Los zapatos de charol han sido una constante, casi un hilo invisible que atraviesa mi infancia. Brillantes, firmes, siempre presentes en cada etapa, cambiando de talla y altura como si crecieran conmigo. Con ellos aprendí —o quizás ya sabía— a bailar cueca, un ritmo que no recuerdo haber incorporado, porque simplemente vive en mí. Hay algo en ese zapateo, en su pulcritud casi ceremonial, que me conecta con una herencia más profunda: la de ser nieta del “Chuico”, y llevar en los pies una memoria que no necesita explicación."
          appleUrl="https://embed.music.apple.com/es/album/el-sombrero-del-huaso/1751391670?i=1751392681"
        />
        <SongCard
          coverImage="/img-lab/zapas/converseblack.JPG"
          coverAlt="Converse"
          text="Las Converse negras llegaron en plena adolescencia, cuando todo era intensidad y referencias prestadas desde otro lugar. Crecí viendo telenovelas y programas argentinos, donde el rock sonaba distinto y los personajes caminaban con una actitud que yo quería imitar —aunque usaran esas zapas Topper que en Chile no existían para mí. Las Converse fueron lo más cercano, y cuando por fin las tuve, sentí que encajaba en esa estética que tanto admiraba. Me las ponía y, de alguna forma, me creía lo más: no por los zapatos en sí, sino por lo que representaban —una versión de mí más segura, más libre, más parecida a lo que imaginaba ser."
          appleUrl="https://embed.music.apple.com/es/album/el-revelde/1443783593?i=1443783609"
        />
        <SongCard
          coverImage="/img-lab/zapas/vansorange.JPG"
          coverAlt="Las Vans"
          text="Las Vans llegaron con la era de Fotolog y Facebook, en un momento donde la identidad también se construía en imágenes. No patinaba, pero usarlas era una forma de pertenecer a ese mundo que mezclaba calle, actitud y cierta rebeldía silenciosa. Me fascinaba que existieran en tantos colores, como si cada par pudiera decir algo distinto. Fue también en esa etapa cuando descubrí a Banksy, Jean-Michel Basquiat y Keith Haring, y todo empezó a encajar: el arte no solo estaba en los museos, también vivía en la calle… y en lo que elegíamos usar."
          appleUrl="https://embed.music.apple.com/es/album/la-rosa-de-los-vientos/682489888?i=682490527"
        />
        <SongCard
          coverImage="/img-lab/zapas/DrMartens.JPG"
          coverAlt="Descripción de la imagen"
          text="Vivía en la lluviosa Ciudad de Buenos Aires, mientras estudiaba Artes Visuales, los borcegos estaban en todas partes: sin importar la marca o el color, eran casi un uniforme compartido. Pero hubo unos en particular que se quedaron conmigo. Me obsesionaban porque, de alguna forma, me recordaban a esos botines ortopédicos que solo conocía por fotos. Tenían una costura amarilla en el borde, un detalle mínimo pero imposible de ignorar; me fascinaba cómo algo tan sutil —la distancia entre las puntadas, el grosor del hilo— podía volver a un zapato completamente reconocible. Con el tiempo, las Dr. Martens se convirtieron en ese par: me han acompañado durante ocho años y siguen intactas, como si el tiempo no pasara del todo por ellas, atravesando distintas versiones de mí sin perder su esencia."
          appleUrl="https://embed.music.apple.com/es/album/bicho-de-ciudad/1811624400?i=1811624413"
        />
        <SongCard
          coverImage="/img-lab/zapas/falcon.JPG"
          coverAlt="Descripción de la imagen"
          text="Las Falcon siempre me gustaron incluso antes de tenerlas, solo por el nombre: me llevaban directo al Millennium Falcon de Han Solo, como si hubiera algo de aventura en ellas. Tenían ese aire retro y deportivo que me recordaba a las zapatillas del colegio —esas blancas, correctas, casi obligatorias— pero completamente reversionadas. Estas, en cambio, estaban llenas de vida: combinaciones de colores inesperadas, juguetonas, casi como si cada par tuviera su propia personalidad. Eran familiares, pero distintas; una forma de volver a lo conocido, pero desde otro lugar."
          appleUrl="https://embed.music.apple.com/es/album/im-into-you/1445220867?i=1445220869"
        />
      </div>
    </div>
  </section>
</article>
