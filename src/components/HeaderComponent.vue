<template>
  <header class="position-relative">
    <nav class="navbar navbar-light px-lg-2 py-4">
      <div class="container-fluid d-flex align-items-center">
        <router-link class="navbar-brand text-center mp-0 fs-4 text-uppercase fw-medium" to="#">
          norm architects
          </router-link>

          <div class="ms-auto d-none d-lg-flex">
            <div class="address mx-5 px-5">
              <p class="fs-6 mb-0 fw-medium">Hello World</p>
              <p class="fs-6 mb-0 fw-medium">+62 896 5057 4913</p>
            </div>

            <div class="language d-flex align-items-center mx-5 pe-5">
              <p class="fs-6 mb-0 d-inline-block me-4 fw-bold">EN</p>
              <p class="fs-6 mb-0 d-inline-block">IDN</p>
            </div>
          </div>
          <button class="navbar-toggler ms-auto ms-lg-0" type="button" data-bs-toggle="collapse"
            data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse mt-3" id="navbarNav">
            <ul class="navbar-nav text-uppercase">
              <li class="nav-item px-0">
                <router-link class="nav-link text-end" aria-current="page" to="#">work</router-link>
              </li>
              <li class="nav-item px-0">
                <router-link class="nav-link text-end" to="#">home</router-link>
              </li>
              <li class="nav-item px-0">
                <router-link class="nav-link text-end" to="#">about</router-link>
              </li>
              <li class="nav-item px-0">
                <router-link class="nav-link text-end" to="#">contact</router-link>
              </li>
            </ul>
          </div>
      </div>
    </nav>
    <section class="px-lg-2">
      <div class="container-fluid">
        <div class="row min-vh-lg-50 pt-5 mt-5">
          <div class="col-lg-5">
            <div class="wrapper d-flex align-items-end h-100">
              <div class="text-uppercase d-flex title-height">
                <h1 class="fw-normal display-3 mp-0">
                  yachtbau
                </h1>
                <p class="mb-0 mt-2 d-none d-lg-block">lorem</p>
              </div>
            </div>
          </div>
          <div class="col-lg-7">
            <div class="wrapper d-lg-flex align-items-lg-end h-100">
              <div class="w-100 d-lg-flex justify-content-lg-evenly title-height">
                <div class="language mt-1 d-none d-lg-block">
                  <p class="fs-6 mb-0 d-inline-block fw-bold">EN</p>
                </div>
                <div class="address mt-1">
                  <p class="fs-6 mb-0">Hello World</p>
                  <p class="fs-6 mb-0">+62 896 5057 4913</p>
                </div>
                <h2 class="fw-normal text-uppercase display-3 mb-0 d-none d-lg-block">
                  next
                </h2>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
}
</script>

