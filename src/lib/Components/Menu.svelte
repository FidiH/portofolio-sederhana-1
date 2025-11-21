<script>


</script>

<section class="py-24 relative">

  <div class="w-full h-full bg-red-300/30">
    <div class="w-32 h-10 top-[30%] absolute -z-10 bg-amber-400 "></div>
    <div class="w-32 -z-10 h-10 right-0 top-[50%] absolute bg-green-800 "></div>
  </div>


  <h2 class="text-3xl text-center my-10 text-amber-500 font-bold">MEMU</h2>
  <div class="columns-1 md:columns-3 gap-1 md:px-[10%]">
    {#each {length: 3}}
    <article class="m-auto w-[80%] rounded mb-7 overflow-hidden shadow-lg">
      <img src="/bg.jpg" alt="">
      <div class="container bg-amber-400">
        <div class="info p-4">
          <h3 class="text-2xl font-semibold">Karedok biasa</h3>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eos vel odio deserunt magni aspernatur doloremque.
          </p>
        </div>
        <div class="p-4 flex justify-between object-center">
          <p class="price font-semibold text-2xl">
            10K
          </p>
          <button type="button" class="py-1 px-3 bg-slate-100 drop-shadow rounded">Beli</button>
        </div>

      </article>
    {/each}
  </div>

</section>