<template>
  <div class="container">
    <nav class="navbar navbar-expand-lg navbar-light py-5">
      <div class="container-fluid">
        <a class="navbar-brand" href="#"
          ><img src="/images/logo-utang.png" alt="" srcset=""
        /></a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div id="navbarSupportedContent" class="collapse navbar-collapse">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <nuxt-link to="/" class="nav-link"> Beranda </nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link to="product" class="nav-link">
                Tentang Produk
              </nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link to="about-us" class="nav-link">
                Tentang Kami
              </nuxt-link>
            </li>
          </ul>
          <div class="d-flex">
            <button class="btn btn-outline-success px-5" type="submit">
              login
            </button>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>
