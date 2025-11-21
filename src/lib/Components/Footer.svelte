<script>

  let link = [
  {
  title: "Karedok Biasa",
  link: "#karedok-biasa"
  },
  {
  title: "Karedok jumbo",
  link: "#karedok-jumbo"
  },
  {
  title: "Karedok spesial",
  link: "#karedok-spesial"
  },
  ]

</script>

<footer class="p-7 md:px-10 -mt-5 bg-amber-400 rounded-t-3xl relative shadow md:">

  <h3 class="text-2xl my-7 font-semibold">Ayo Coba, nikmati rasanya</h3>

<div class="md:columns-3">

  <nav class="container my-5 md:my-0">
    <h4 class="text-lg font-bold">Karedok culture</h4>
    {#each link as lk}
    <a class="block text-sm font-semibold opacity-70" href="{lk.link}">{lk.title}</a>
    {/each}
  </nav>
  <nav class="container my-5">
    <h4 class="text-lg font-bold">Lainnya</h4>
    {#each link as lk}
    <a class="block text-sm font-semibold opacity-70" href="{lk.link}">{lk.title}</a>
    {/each}
  </nav>
  
  
  <article>
    <h3 class="font-bold text-lg">Hubungi kami</h3>
    <p>WhatsApp: 083116293051</p>
    <p>E-mail: TestingKaredok@gmail.com</p>
    <p>Alamay: Jln Kedungreja, Kab. cilacap</p>
  </article>
  
  </div>

</footer>