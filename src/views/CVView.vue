<script setup>
import Offcanvas from '@/components/Offcanvas.vue'
import Footer from '@/components/Footer.vue'
</script>

<template>
  <main style="display: inline-block">
    <div class="col-4">
      <Offcanvas />
    </div>
    <div id="main-content" class="container text-center col-8">
      <h1>📝 Resume</h1>
      <div class="row">MARTAS THE ATOM GAUTAM</div>
      <h3>AI & ML ENGINEER</h3>
      <br>
      <!-- <div class="row">
        <embed src="../assets/resume.pdf" height="1000rem" width="30rem" />
      </div> -->
      <iframe id="my_pdf" src="../assets/resume.pdf" frameborder="0"></iframe>
    </div>
    <br>
    <div style="display: flex; justify-content: center;">
      <a href="../assets/resume.pdf" download><button class="btn btn-primary">Download CV</button></a>
    </div>
    <br>
    <Footer style="margin-right: 10rem; margin-left: 10rem"></Footer>
  </main>
</template>

<style>
#my_pdf {
  width: 40rem;
  height: 975px;
}

#main-content {
  margin-top: 2rem;
  color: aliceblue;
}
</style>
