<template>
  <div class="courses-page">
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
  </div>
</template>

<script>
import CourseBox from './../components/CourseBox.vue';

export default{
  name: "Courses",
  components: {
    CourseBox,
  },



  
}

</script>

<style>



</style>
