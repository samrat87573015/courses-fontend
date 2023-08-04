
<template>
  <main>
    <section>
      <div class="banner_area overlay h-[700px] flex items-center !bg-cover !bg-center !bg-no-repeat">
        <div class="container">
          <div class="gird grid-cols-1 items-center">
            <div class="space-y-5 px-4 md:px-0 banner_content relative z-10">
              <h6 class="text-white text-xl font-medium">For Your Better Life</h6>
              <h1 class="lg:text-7xl md:text-6xl text-3xl text-white font-bold">Build Better Life Today<br>
                with <span class="text-[#eba504]">Jessica Hische</span></h1>
              <div class="btn_area">
                <RouterLink to="/courses" class="btn">All Courses</RouterLink>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section>
      <div class="courses-area py-28">
        <div class="container">
          <div class="space-y-3 section_title_area mb-14 text-center">
            <span class="text-[#F14D5D] text-2xl font-medium">Popular Courses</span>
            <h2 class="md:text-6xl text-3xl font-bold">Choose the Most Suitable<br>
              Course For You</h2>
          </div>
          <div class="grid xl:grid-cols-3 md:grid-cols-2 grid-cols-1 gap-5">
            <CourseBox :key="course" v-for="course in 9" />
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
import CourseBox from './../components/CourseBox.vue';

export default{
  name: "Home",
  components: {
    CourseBox,
  },



  
}

</script>
