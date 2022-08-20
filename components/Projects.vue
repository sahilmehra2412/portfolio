<template>
    <section id="project" class="bg-white dark:bg-gray-900">
  <div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-16 lg:px-6 ">
      <div class="mx-auto max-w-screen-sm text-center mb-8 lg:mb-16">
          <h2 class="mb-4 text-4xl tracking-tight font-extrabold text-gray-900 dark:text-white">Projects</h2>
      </div> 
      <div class="grid gap-8 mb-6 lg:mb-16 md:grid-cols-2">
          <div class="items-center bg-gray-50 rounded-lg shadow sm:flex dark:bg-gray-800 dark:border-gray-700">
              <a href="#">
                  <img class="w-full rounded-lg sm:rounded-none sm:rounded-l-lg" src="../assets/images/cloud.png" alt="Portfolio">
              </a>
              <div class="p-5">
                  <h3 class="text-xl font-bold tracking-tight text-gray-900 dark:text-white">
                      <a href="#">Portfolio</a>
                  </h3>
                  <span class="text-gray-500 dark:text-gray-400">[Nuxt.js, TailwindCSS]</span>
                  <p class="mt-3 mb-4 font-light text-gray-500 dark:text-gray-400">Made this Portfolio website by using Nuxt.js and TailwindCSS</p>
              </div>
          </div> 
          <div class="items-center bg-gray-50 rounded-lg shadow sm:flex dark:bg-gray-800 dark:border-gray-700">
              <a href="#">
                  <img class="w-full rounded-lg sm:rounded-none sm:rounded-l-lg" src="../assets/images/friends.png" alt="Friends Episode Finder">
              </a>
              <div class="p-5">
                  <h3 class="text-xl font-bold tracking-tight text-gray-900 dark:text-white">
                      <a href="#">Friends' Episode Finder</a>
                  </h3>
                  <span class="text-gray-500 dark:text-gray-400">[Python, TailwindCSS, Express]</span>
                  <p class="mt-3 mb-4 font-light text-gray-500 dark:text-gray-400">Search any Friends' episode just by dialogues.</p>

              </div>
          </div> 
          <div class="items-center bg-gray-50 rounded-lg shadow sm:flex dark:bg-gray-800 dark:border-gray-700">
              <a href="#">
                  <img class="w-full rounded-lg sm:rounded-none sm:rounded-l-lg" src="../assets/images/attendance.png" alt="Teacher Attendence System">
              </a>
              <div class="p-5">
                  <h3 class="text-xl font-bold tracking-tight text-gray-900 dark:text-white">
                      <a href="#">Teacher Attendence System</a>
                  </h3>
                  <span class="text-gray-500 dark:text-gray-400">[Python, Flask]</span>
                  <p class="mt-3 mb-4 font-light text-gray-500 dark:text-gray-400">System for Teachers to maintain students Attendence.</p>
              </div>
          </div> 
          <div class="items-center bg-gray-50 rounded-lg shadow sm:flex dark:bg-gray-800 dark:border-gray-700">
              <a href="#">
                  <img class="w-full rounded-lg sm:rounded-none sm:rounded-l-lg" src="../assets/images/test-portal.png" alt="Test Portal">
              </a>
              <div class="p-5">
                  <h3 class="text-xl font-bold tracking-tight text-gray-900 dark:text-white">
                      <a href="#">Online Test Portal</a>
                  </h3>
                  <span class="text-gray-500 dark:text-gray-400">[Python, Flask]</span>
                  <p class="mt-3 mb-4 font-light text-gray-500 dark:text-gray-400">Online Test Portal for Students to take online quizes.</p>
              </div>
          </div>  
      </div>  
  </div>
</section>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    @media (min-width: 640px){
        img{
            width: 300px;
            max-width: 250px;
        }
    }
    @media(max-width: 640px){
        img{
            width: 100%;
            object-fit: cover;
        }
    }
    img {
        height: 220px;
    }
</style>