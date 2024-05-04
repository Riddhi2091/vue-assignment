<script setup>

</script>

<template>
  <nav class="navbar d-flex  navbar-expand-lg navbar-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#"><img class="logo" src="../assets/img/logo.png" alt=""></a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0 ms-3">
          <li class="nav-item mx-md-3">
            <a class="nav-link active" aria-current="page" href="#">Asset Managers</a>
          </li>
          <li class="nav-item mx-md-3">
            <a class="nav-link active" aria-current="page" href="#">Asset Owners</a>
          </li>
          <li class="nav-item mx-md-3">
            <a class="nav-link active" aria-current="page" href="#">Investors</a>
          </li>
          <li class="nav-item mx-md-3">
            <a class="nav-link active" aria-current="page" href="#">Service Providers </a>
          </li>
          <li class="nav-item mx-md-3">
            <a class="nav-link active" aria-current="page" href="#">About StegX</a>
          </li>
        </ul>

        <a href="#" class="btn nav-button me-md-5">Book a demo</a>
      </div>
    </div>
  </nav>
</template>


<style scoped>
.navbar {
  opacity: 0.8;
  background-color: #000000;
  border-bottom: 4px solid #781fff;
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 1000;
}

.logo {
  width: 220px;
  margin: auto;
}

.nav-link {
  text-transform: uppercase;
  font-size: 12px;
}

.nav-link:hover {
  font-weight: 800;
}

.nav-button {
  background-image: linear-gradient(315deg, #3f0efa, #90f);
  color: #ffff;
  padding: 10px 24px;
  border: none;
  border-radius: 10px;
}

.nav-button:hover {
  opacity: 0.8;
  padding: 10px 23px;
}
</style>
