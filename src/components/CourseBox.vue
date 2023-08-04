<template>
    <div>
        <div class="courses_itam bg-white custom_shadow relative rounded-xl overflow-hidden">
            <div class="relative">
              <img class="rounded-xl" src="@/assets/img/courses/course_image7.jpg" alt="">
              <div class="cat absolute top-0 left-0 text-white">
                <ul class="flex gap-2 p-5">
                  <li class="odd:bg-green-500 p-2 leading-none rounded-md">Data</li>
                  <li class="even:bg-red-500 p-2 leading-none rounded-md">Marketing</li>
                </ul>
              </div>
            </div>
            <div class="courses_content space-y-5 p-8 relative">
              <div class="price absolute -top-[40px] right-8 bg-[#F14D5D] text-white min-w-[70px] min-h-[70px] text-center leading-[70px] rounded-full">
                <span class="font-medium">$500</span>
              </div>
              <div class="flex justify-between">
                <div class="dificalty_lavel ">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class=" text-[#F14D5D] w-6 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M3 13.125C3 12.504 3.504 12 4.125 12h2.25c.621 0 1.125.504 1.125 1.125v6.75C7.5 20.496 6.996 21 6.375 21h-2.25A1.125 1.125 0 013 19.875v-6.75zM9.75 8.625c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125v11.25c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V8.625zM16.5 4.125c0-.621.504-1.125 1.125-1.125h2.25C20.496 3 21 3.504 21 4.125v15.75c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V4.125z" />
                  </svg>
                  <span class="ml-2 font-medium">Beginner</span>                 
                </div>
                <div class="duration">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="text-[#F14D5D] w-6 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M12 6v6h4.5m4.5 0a9 9 0 11-18 0 9 9 0 0118 0z" />
                  </svg>
                  <span class="ml-2 font-medium">10+ Hours</span>                  
                </div>
              </div>
              <div class="mb-5">
                <h2 class="text-2xl font-semibold"><RouterLink to="#">Strategy law and Organization Foundation</RouterLink> </h2>
              </div>
              <div class="flex items-center mb-5">
                <div class="w-10 h-10 mr-4">
                  <img class="rounded-full" src="@/assets/img/author/author.png" alt="">
                </div>
                <div>
                  <span>David MacLean</span>
                </div>
              </div>
              <div class="border-t-2 pt-8">
                <RouterLink class="font-medium text-[#F14D5D] hover:text-gray-950 text-base underline" to="#">Know Details<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M4.5 12h15m0 0l-6.75-6.75M19.5 12l-6.75 6.75" />
                </svg>
                </RouterLink>
              </div>

            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "CourseBox",
}
</script>

<style scoped>

</style>