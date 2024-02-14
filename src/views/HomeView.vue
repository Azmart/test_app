<script setup>
import Offcanvas from '@/components/Offcanvas.vue'
import Footer from '@/components/Footer.vue'
import Skills from '@/components/Skills.vue'
import Research from '@/components/Research.vue'
</script>

<template>
  <main style="display: inline-block">
    <div class="col-4">
      <Offcanvas />
    </div>
    <div id="main-content" class="container text-center col-8">
      <div class="row">
        <div class="mb-3">
          <iframe
            src="https://lottie.host/embed/5c671c48-76e9-4dd3-bae6-a119f2839bc0/pXzvaPoRWa.json"
          ></iframe>
          <label for="exampleFormControlTextarea1" class="form-label"
            >After providing OpenAI API Key in the sidebar, you can send your questions and hit
            Enter to know more about me from my AI agent, Chankhe!</label
          >
          <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
          <br />
        </div>
        <br />
        <div style="display: inline-flex">
          <div class="col-9">
            <div class="card" id="intro">
              <div class="card-body" style="height: 15rem;">
                <h1 class="card-title" style="color: aliceblue">
                  Hi, I'm Martas the Atom Gautam👋
                </h1>
                <br>
                <p class="card-text" style="color: aliceblue">
                  <b>
                    An AI student at HKBU and an AI enthusiast at <br />
                    कृत्रिम बौद्धिकता। Kribaat
                  </b>
                </p>
              </div>
            </div>
            <div>
              <p>
                I'm passionate about leveraging AI & ML to drive R&D while generating meaningful
                insights and solutions in business. Check out my AI R&D startup at kribaat.com
              </p>
            </div>
          </div>
          <div class="col-3">
            <iframe
              src="https://lottie.host/embed/1576ab6e-ea15-4c73-99e5-7db125a64826/f3GMo4lqcC.json"
            ></iframe>
          </div>
        </div>
        <br />
        <br />

        <Skills></Skills>
        <br />
        <Research></Research>
        <div>
          <Footer id="footer"></Footer>
        </div>
      </div>
    </div>
  </main>
</template>

<style>
#content {
  margin-top: 2rem;
}

.mb-3 {
  text-align: center;
}

#intro {
  background: linear-gradient(to right, #ffd4dd, #000395);
  color: aliceblue;
}

#main-content {
  color: aliceblue;
  margin-top: 2rem;
}

.skills {
  width: 10rem;
}


/* #footer{
    background-color: #fff;
} */
</style>

<script></script>
