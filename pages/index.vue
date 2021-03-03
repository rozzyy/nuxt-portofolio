<template>
  <div>
    <!-- navbar -->
     <b-navbar toggleable="lg" type="light" variant="transparent" class="container">
      <b-navbar-brand href="#" class="font-weight-bold" style="font-size: 30px">rrahmanda</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
           <b-navbar-nav>
            <b-nav-item href="#" active class="font-weight-bold">HOME</b-nav-item>
            <b-nav-item href="#" class="font-weight-bold">ABOUT </b-nav-item>
            <b-nav-item href="#" class="font-weight-bold">SKILLS</b-nav-item>
            <b-nav-item href="#" class="font-weight-bold">PROJECTS</b-nav-item>
            <b-nav-item href="#" class="font-weight-bold">CONTACT</b-nav-item>
          </b-navbar-nav>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
    <div class="container">
     <b-row>
       <b-col style="margin-top: 200px;" sm="7">
          <h5>Hello! I Am Rozzy Rahmanda</h5>
          <h2 class="font-weight-bold">I AM &lt; FULLSTACK DEVELOPER /&gt;</h2>
          <p>
            I'm a Web and Android Developer based in Medan. I build web and mobile apps with beautiful and cool design.
          </p>
          <b-row>
            <b-col>
              <b-button variant="outline-dark" class="container">Download CV</b-button>
            </b-col>
            <b-col>
              <b-button variant="outline-dark" class="container">Hire Me!</b-button>
            </b-col>
          </b-row>
       </b-col>
       <b-col>
         <div class="border border-dark">
           Ilustrasi
         </div>
       </b-col>
     </b-row>
    </div>
  </div>
</template>

<script>
import image from '@/assets/back-image.jpg'
export default {
  data () {
    return {
      gambar: image
    }
  }
}
</script>

<style scoped>
.back-image {
  background: url('~assets/back-image.jpg') rgb(61, 59, 59, 0.8);
  background-size: cover;
  background-blend-mode: multiply;
  height: 100vh;
}
body, html {
  height: 100%;
}
</style>
