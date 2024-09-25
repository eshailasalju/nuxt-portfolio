<template>
    <section id="bg">
        <div class="relative z-10">
            <div class="justify-center grid grid-cols-2 gap-20 ">
                <div id="col-1" class="justify-center flex flex-col justify-center ml-6">
                    <h1 class="text-6xl antialiased font-bold text-left" id="judul">Eshaila Amanda Salju</h1>
                    <p class="text-xl">UI/UX Designer</p>
                </div>
                <div class="items-center justify-content-center">
                    <img class="items-center justify-content-center" id="photo-profile" src="../assets/img/salju.png">
                </div>
            </div>
        </div>
    </section>

    <section id="bg-2">
        <h1 class="text-center text-5xl font-bold text-white mt-6 mb-8" id="judul">Ketrampilan  </h1>
        <div class="flex flex-col justify-center mt-6 mb-8">
            <div class="p-10 grid grid-cols-3 gap-8">
            <div>
                <a href="#" id="card" class="block max-w-sm p-6 rounded-lg dark:bg-gray-800 dark:border-gray-700 h-96 flex flex-col justify-center">
                    <img id="card-img" src="../assets/img/ui.jpg">
                    <h5 class="mb-2 text-2xl font-bold tracking-tight text-center pt-5">UI/UI Designer</h5>
                </a>
            </div>
            <div>
                <a href="#" id="card" class="block max-w-sm p-6 rounded-lg dark:bg-gray-800 dark:border-gray-700 h-96 flex flex-col justify-center">
                    <img id="card-img-2" src="../assets/img/data.jpg">
                    <h5 class="mb-2 text-2xl font-bold tracking-tight text-center pt-5">Data Analis</h5>
                </a>
            </div>
            <div>
                <a href="#" id="card" class="block max-w-sm p-6 rounded-lg dark:bg-gray-800 dark:border-gray-700 h-96 flex flex-col justify-center">
                    <img id="card-img-3" src="../assets/img/konten.jpg">
                    <h5 class="mb-2 text-2xl font-bold tracking-tight text-center pt-5">Konten Kreator</h5>
                </a>
            </div>
        </div>
        </div>
    </section>
    
    <section id="bg">
      <div class="relative z-10">
          <h1 class="text-center text-5xl font-bold mb-8" id="judul">Pengalaman</h1>
          <div class="flex flex-col justify-center items-center mt-6 mb-8">
              <div class="grid grid-cols-1 ">
                  <div class="rounded-lg p-8 text-center h-96 w-96 flex flex-col justify-center items-center" id="card">
                      <img class="h-40 mx-auto" id="card-img-5" src="../assets/img/hmpsti.jpg">
                      <h3 class="text-2xl font-bold mb-2">HMPSTI</h3>
                      <p class="font-medium text-gold">Wakahim</p>
                  </div>
              </div>
          </div>
      </div>
    </section>
    
    <section class="justify-center items-center bg-black p-10 text-white">
      <div class="text-center">
    <p> &copy; Eshaila Amanda Salju. All Rights reserved.</p>
    </div>
    </section>
</template>
  
<script>
</script>
<style>
#bg {
  position: relative;
  padding-top: 80px;
  padding-bottom: 150px;
  padding-left: 80px;
  padding-right: 80px;
  z-index: 1;
}

#bg-2{
    background-color: #f2aeff;
    background-size: cover;
    padding-top: 40px;
    padding-bottom: 40px;
    padding-left: 80px;
    padding-right: 80px;
}
#card{
background-color: #ffffff;
filter: drop-shadow(-6px 6px 11px #f79cff);
transition: 0.3s;
}

#card-img {
  transition: 0.5s;
}
#card-img-2 {
  transition: 0.5s;
}
#card-img-3 {
  transition: 0.5s;
}
#card-img-4 {
  transition: 0.5s;
}
#card-img-5 {
  transition: 0.5s;
}
#card-img-6 {
  transition: 0.5s;
}

</style>
  