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
      <div class="row">
        <h1>🤠 My Hobbies</h1>
      </div>
      <div>
        <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="false">
          <div class="carousel-indicators">
            <button
              type="button"
              data-bs-target="#carouselExampleCaptions"
              data-bs-slide-to="0"
              class="active"
              aria-current="true"
              aria-label="Slide 1"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleCaptions"
              data-bs-slide-to="1"
              aria-label="Slide 2"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleCaptions"
              data-bs-slide-to="2"
              aria-label="Slide 3"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleCaptions"
              data-bs-slide-to="3"
              aria-label="Slide 4"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleCaptions"
              data-bs-slide-to="4"
              aria-label="Slide 5"
            ></button>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="../assets/hobbies/20231119_064608.jpg" class="d-block w-100" alt="..." />
              <div class="carousel-caption d-none d-md-block" style="color: aqua;">
                <h5>Hiking</h5>
                <!-- <p>Some representative placeholder content for the first slide.</p> -->
              </div>
            </div>
            <div class="carousel-item">
              <img src="../assets/hobbies/20240214_145732.jpg" class="d-block w-100" alt="..." />
              <div class="carousel-caption d-none d-md-block" style="color: rgb(209, 255, 3);">
                <h5>Nunismatics</h5>
                <!-- <p>Some representative placeholder content for the second slide.</p> -->
              </div>
            </div>
            <div class="carousel-item">
              <img src="../assets/hobbies/20240214_150451.jpg" class="d-block w-100" alt="..." />
              <div class="carousel-caption d-none d-md-block" style="color: rgb(0, 255, 157); font-weight: bold;">
                <h5><span style="background:;">Cooking</span></h5>
                <!-- <p>Some representative placeholder content for the third slide.</p> -->
              </div>
            </div>
            <div class="carousel-item">
              <img src="../assets/hobbies/FB_IMG_1700723115624.jpg" class="d-block w-100" alt="..." />
              <div class="carousel-caption d-none d-md-block" style="color: rgb(4, 103, 42);">
                <h5 style="font-weight: bolder;">Manga & Anime</h5>
                <!-- <p>Some representative placeholder content for the third slide.</p> -->
              </div>
            </div>
            <div class="carousel-item">
              <img src="../assets/hobbies/IMG_20240128_210704_828.jpg" class="d-block w-100" alt="..." />
              <div class="carousel-caption d-none d-md-block">
                <h5>Cars</h5>
                <!-- <p>Some representative placeholder content for the third slide.</p> -->
              </div>
            </div>
          </div>
          <button
            class="carousel-control-prev"
            type="button"
            data-bs-target="#carouselExampleCaptions"
            data-bs-slide="prev"
          >
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button
            class="carousel-control-next"
            type="button"
            data-bs-target="#carouselExampleCaptions"
            data-bs-slide="next"
          >
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </div>
      <div>
        <Footer id="footer"></Footer>
      </div>
    </div>
  </main>
</template>


<style>
#carouselExampleCaptions {
  height: 30rem;
}

img{
  height:30rem;
  object-fit: contain;
}

</style>