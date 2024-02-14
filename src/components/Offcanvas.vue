<template>
  <div>
    <button
      class="btn btn-primary"
      type="button"
      data-bs-toggle="offcanvas"
      data-bs-target="#offcanvasScrolling"
      aria-controls="offcanvasScrolling"
      style="margin-top: 1rem; position: absolute; right: 0; margin-right: 1rem"
    >
      Menu
    </button>
  </div>

  <div
    class="offcanvas offcanvas-end show"
    tabindex="-1"
    id="offcanvasScrolling"
    data-bs-scroll="true"
    data-bs-backdrop="false"
    aria-labelledby="offcanvasScrollingLabel"
  >
    <div class="offcanvas-header">
      <h5 class="offcanvas-title" id="offcanvasScrollingLabel" style="color: aliceblue">
        Martas's Website
      </h5>
      <button
        type="button"
        class="btn-close text-reset"
        data-bs-dismiss="offcanvas"
        aria-label="Close"
      ></button>
    </div>
    <div class="offcanvas-body">
      <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="/">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/projects">Projects</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/cv">CV</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/hobbies">Hobbies</a>
        </li>
      </ul>
    </div>
    <div class="offcanvas-body">
      <p style="text-align: center;">Enter your OpenAI API Key and click Submit!</p>
      <form class="d-flex mt-3" role="search">
        <input class="form-control me-2" type="search" placeholder="API Key" aria-label="Search" />
        <button class="btn btn-success" type="submit">Submit</button>
      </form>
    </div>
    <div class="offcanvas-body">
      <div class="image-box">
        <a :href="linkedInURL" target="_blank">
          <img src="https://media.licdn.com/dms/image/D5603AQEA1wx0xzTi8A/profile-displayphoto-shrink_400_400/0/1673881666381?e=1710374400&v=beta&t=XvoPhlJ_fnWVOcHieVtH9aLNfahtIQym7CLAwqu9r6g" alt="LinkedIn Profile Picture" class="social-icon" />
        </a>
      </div>
    </div>
  </div>
</template>

<style>
#offcanvasScrolling {
  background: linear-gradient(to top, #ffd4dd, #000395);
}

.offcanvas-body {
  color: aliceblue;
}

.social-icon{
  height: 15rem; 
  width: 15rem;
  border-radius: 1em;
  margin-left: 4em;
}

</style>

<script>

export default{
  data() {
    return {
      linkedInURL: "https://www.linkedin.com/in/martas-the-atom-gautam-a7a714188/"
    };
  },
};
</script>
