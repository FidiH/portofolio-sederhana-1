
<script>
  
  import {onMount} from "svelte"
  
  
  let gelapkan = false
  // klien
  onMount(() => {
    window.addEventListener("scroll", () => {
      if(window.scrollY > 200){
        gelapkan = true
      }else{
        gelapkan = false
      }
    })
  })
  
</script>

<header class="fixed z-50 w-screen p-7">
  <div class="flex px-4 py-2 md:px-7 md:py-3 items-center justify-between drop-shadow rounded w-full transition-all {gelapkan ? 'bg-green-800/100' : 'bg-slate-100/20'}">
    
    <h1 class="text-lg drop-shadow text-slate-50 font-semibold">Karedok-culture</h1>
    
    <button class="invert drop-shadow md:hidden ">
      <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" viewBox="0 0 16 16">
        <path fill-rule="evenodd" d="M2.5 12a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5m0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5m0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5" />
      </svg>
    </button>
    
    <nav class="hidden md:flex w-[30%] text-slate-50 justify-between">
      <a href="#">Menu</a>
      <a href="#">Cerita</a>
      <a href="#">Galeri</a>
      <a href="#">Kontak</a>
    </nav>
    
  </div>
</header>

<style>
  nav a{
    display: block;
  }
</style>