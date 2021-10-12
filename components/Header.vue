<template>
  <header class="header">
    <div class="header__container container py-3">
      <div class="row align-items-center">
        <div class="col-md-9">
          <a href="/">
            <img
              class="img-fluid"
              src="~/assets/images/logoblanco.png"
              alt=""
            />
          </a>
        </div>
        <div class="col-md-3 d-flex justify-content-end">
          <a class="d-none d-md-block btn btn-light px-5 text-orange"
            >Registrarse</a
          >
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {}
</script>

<style>
header {
  background-color: #ff6600;
}

.text-orange {
  color: #ff6600;
}
</style>
