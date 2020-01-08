<template>
 <div> 
  <TopBar />

  <!-- Main Content -->
    <div class="flex flex-col md:flex-row md: justify-between">
      <!-- Left Bar -->
      <div class="flex md:flex-col md:w-1/3">
        <div class="p-10">
          <img src="https://res.cloudinary.com/alexoc/image/upload/v1559398220/WhatsApp_Image_2019-02-23_at_11.14.29_npbmms.jpg" alt=""
            class=" w-32 h-32 rounded-full object-cover">
          <div class="my-6">
            <p class="text-2xl text-blue-400">Alex Cosmas</p>
            <h1 class="text-2xl font-bold text-blue-500">Multi Discipline
              Project
              Manager</h1>
          </div>

          </h1>
          <!-- Description-->
          <div>
            <p class=" text-lg leading-relaxed">
              Hello, <br>
              I am a Multi-disciplined project manager based in Nairobi, KE.
              I design website and develop web applications. I currently work
              with
              Protec Consulting to deliver solutions for their objectives
              through
              design and technology.
              Prior to that, I spent time working in the Department of Defence
              as well
              as local governemtn, during which time I founded PIOPost - a
              socila
              management platform for public safety
            </p>
          </div>

          <div class="my-6">
            <p class="text-2xl text-blue-400">Social Media</p>

            <ul class="flex">
              <li class="">LinkedIn</li>
              <li class="pl-3">Twitter</li>
              <li class="pl-3">YouTube</li>
            </ul>

          </div>

        </div>
      </div>
      <!-- Right Bar -->
      <div class="flex md:flex-col md:w-2/3">
        <div class=" bg-gray-400">
          <div class="p-10">

            <!-- Main Menu -->
            <div class="flex">
              <ul class="flex text-lg font-bold text-blue-500">
                <nuxt-link to=""><li class="px-0">My Process</li></nuxt-link>
                <nuxt-link to=""><li class="px-5">Work Done</li></nuxt-link>
                <nuxt-link to=""><li class="px-5">Blog</li></nuxt-link>
                <nuxt-link to=""><li class="px-5">Hire Me</li></nuxt-link>
              </ul>

              <img src="" alt="">
            </div>

            <div>
              <!-- Tabs -->
              <div class="my-6 text-lg">
                <ul class="flex flex-row">
                  <nuxt-link to=""><li class="px-0">All</li></nuxt-link>
                  <li class="pl-5">Live</li class="pl-5">
                  <li class="pl-5">In Production</li>
                  <li class="pl-5">Rebuilds</li>
                </ul>
              </div>

              <!--Cards-->
              <div class="flex flex-wrap">
                <div
                  class="md:w-2/5 p-2 border-b-2 border-blue-600 rounded-br-lg rounded-bl-lg px-6 mr-5 my-5 shadow-xl bg-white">
                  <div>
                    <h1 class="text-lg text-blue-500 font-bold">Code to Solve
                    </h1>
                    <p class="my-3 text-lg">Find state-licensed treatment near
                      you for
                      your addiction
                      and
                      substance use disorder</p>
                    <div id="techstack" class="flex flex-col">
                      <p class="mb-5">Tech Stack<span>NuxtJS,
                          TailwindCSS, StrapiCMS,
                          MongoDB</span></p>
                    </div>
                  </div>
                </div>
                <div
                  class="md:w-2/5 p-2 border-b-2 border-blue-600 rounded-br-lg rounded-bl-lg px-6 mr-5 my-5 shadow-xl bg-white">
                  <div>
                    <h1 class="text-lg text-blue-500 font-bold">New Age Media
                    </h1>
                    <p class="my-3 text-lg">Find state-licensed treatment near
                      you for
                      your addiction
                      and
                      substance use disorder</p>
                    <div id="techstack" class="flex flex-col">
                      <p class="mb-5">Tech Stack<span>NuxtJS,
                          TailwindCSS, StrapiCMS,
                          MongoDB</span></p>
                    </div>
                  </div>
                </div>

                <div
                  class="md:w-2/5 p-2 border-b-2 border-blue-600 rounded-br-lg rounded-bl-lg px-6 mr-5 my-5 shadow-xl bg-white">
                  <div>
                    <h1 class="text-lg text-blue-500 font-bold">Idyll Media
                      Solutions
                    </h1>
                    <p class="my-3 text-lg">Find state-licensed treatment near
                      you for
                      your addiction
                      and
                      substance use disorder</p>
                    <div id="techstack" class="flex flex-col">
                      <p class="mb-5">Tech Stack <br> <span>NuxtJS,
                          TailwindCSS, StrapiCMS,
                          MongoDB</span></p>
                    </div>
                  </div>
                </div>

                <div
                  class="md:w-2/5 p-2 border-b-2 border-blue-600 rounded-br-lg rounded-bl-lg px-6 mr-5 my-5 shadow-xl bg-white">
                  <div>
                    <h1 class="text-lg text-blue-500 font-bold">Protec
                      Consulting
                    </h1>
                    <p class="my-3 text-lg">Find state-licensed treatment near
                      you for
                      your addiction
                      and
                      substance use disorder</p>
                    <div id="techstack" class="flex flex-col">
                      <p class="mb-5">Tech Stack<span>Frontend: NuxtJS,
                          TailwindCSS, StrapiCMS,
                          MongoDB</span></p>
                    </div>
                  </div>
                </div>

                <div
                  class="md:w-2/5 p-2 border-b-2 border-blue-600 rounded-br-lg rounded-bl-lg px-6 mr-5 my-5 shadow-xl bg-white">
                  <div>
                    <h1 class="text-lg text-blue-500 font-bold">Advent Safaris
                    </h1>
                    <p class="my-3 text-lg">Find state-licensed treatment near
                      you for
                      your addiction
                      and
                      substance use disorder</p>
                    <div id="techstack" class="flex flex-col">
                      <p class="mb-5">Tech Stack<span>Frontend: NuxtJS,
                          TailwindCSS, StrapiCMS,
                          MongoDB</span></p>
                    </div>
                  </div>
                </div>


                <div
                  class="md:w-2/5 p-2 border-b-2 border-blue-600 rounded-br-lg rounded-bl-lg px-6 mr-5 my-5 shadow-xl bg-white">
                  <div>
                    <h1 class="text-lg text-blue-500 font-bold">CASDA Africa
                    </h1>
                    <p class="my-3 text-lg">Find state-licensed treatment near
                      you for
                      your addiction
                      and
                      substance use disorder</p>
                    <div id="techstack" class="flex flex-col">
                      <p class="mb-5">Tech Stack<span>Frontend: NuxtJS,
                          TailwindCSS, StrapiCMS,
                          MongoDB</span></p>
                    </div>
                  </div>
                </div>





              </div>




            </div>
          </div>
        </div>
      </div>
    </div>


  
  
 </div>
</template>

<script>
import TopBar from '~/components/TopBar.vue'

export default {
  components: {
    TopBar
  }
}
</script>
