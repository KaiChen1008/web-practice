<template>

  <!-- <img src="https://via.placeholder.com/400x400" alt="a image"> -->
  <nav class="py-4">
    <div class="container mx-auto flex flex-col sm:flex-row justify-between items-center sm:items-baseline">
      <div class="bg-gray-300 rounded-xl" style="width:120px; height: 30px"></div>
      <ul class="flex justify-left text-xl font-medium mt-4 sm:mt-0">
        <li class="mr-4">Home</li>
        <li class="mr-4">About</li>
        <li class="mr-4">Things</li>
      </ul>
    </div>
  </nav>

  <header class='bg-gray-400 header flex justify-center items-center' >
    <h1 class='p-6 text-white text-4xl bg-gray-800 font-medium rounded-xl'>Welcome to My Webpage</h1>
  </header>

  <section class="py-10 px-2">
    <div class="container mx-auto max-w-3xl">
      <h2 class="text-3xl text-center mb-6 font-medium">
        About Me
      </h2>
      <p class="leading-loose">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugit ipsam esse repellendus nesciunt eaque consequatur! Cumque id sit perspiciatis, fuga placeat obcaecati veniam tenetur asperiores, optio dignissimos nam rem dicta dolor suscipit cum! Quidem sequi exercitationem ad aperiam nihil rem fugiat illo commodi tenetur minima a blanditiis necessitatibus quis animi totam nemo odit, omnis, recusandae dolor. Perferendis consequuntur, suscipit iste ducimus, possimus consequatur doloribus debitis magni esse molestias ratione animi repellendus laborum laudantium at sapiente ullam necessitatibus asperiores accusantium eius.
      </p>
    </div>
  </section>

  <section class="py-10 bg-blue-100">
    <div class="container mx-auto max-w-3xl">
      <div class="px-2">
        <div class="flex flex-wrap -mx-2">
          <div class="w-full sm:w-5/12 px-2 flex justify-center">
            <div class="rounded bg-gray-300 w-4/5 sm:w-full" style="height:250px"> </div>
          </div>
          <div class="w-full sm:w-7/12 px-2 mt-6 sm:mt-0 ">
            <div class="rounded " style="height:250px">
              <h2 class="text-2xl font-medium mb-6 text-center sm:text-left">Who am I</h2>
              <p class="leading-loose text-bg">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos necessitatibus sit, consequuntur rerum aspernatur, minima atque aliquid asperiores ab veritatis laboriosam consectetur corporis, omnis ratione nulla amet voluptate tempore id.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>     
  </section>
  
  <section class="py-10">
    <div class="container mx-auto">
      <h2 class="text-3xl text-center mb-6 font-medium">
        4 Things
      </h2>
      <div class="flex flex-wrap -mx-2">
        <div class="w-full sm:w-3/12 px-2 flex flex-col items-center mt-4">
          <div class="rounded bg-gray-300 w-2/5 sm:w-full" style="height:150px"></div>
          <h3 class="uppercase text-center text-xl font-medium mt-2">quailty</h3>
        </div>
        <div class="w-full sm:w-3/12 px-2 flex flex-col items-center mt-4">
          <div class="rounded bg-gray-300 w-2/5 sm:w-full" style="height:150px"></div>
          <h3 class="uppercase text-center text-xl font-medium mt-2">quailty</h3>
        </div>
        <div class="w-full sm:w-3/12 px-2 flex flex-col items-center mt-4">
          <div class="rounded bg-gray-300 w-2/5 sm:w-full" style="height:150px"></div>
          <h3 class="uppercase text-center text-xl font-medium mt-2">quailty</h3>
        </div>
        <div class="w-full sm:w-3/12 px-2 flex flex-col items-center mt-4">
          <div class="rounded bg-gray-300 w-2/5 sm:w-full" style="height:150px"></div>
          <h3 class="uppercase text-center text-xl font-medium mt-2">quailty</h3>
        </div>
        
      </div>
    
    </div>
  </section>

  <footer class="py-5 bg-purple-800 text-center text-bg font-medium text-white">
    Design by dppa
  </footer>

</template>

<script setup>

</script>

<style scoped>
.header {
  height: 500px
}
</style>
