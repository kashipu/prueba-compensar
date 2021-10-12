<template>
  <div>
    <Header />
    <div class="container mt-5">
      <div class="row">
        <div class="col-md-7">
          <div class="index__title">
            <h1>¡Aquí se construye el sueño de tener casa propia!</h1>
            <p>
              Busca proyectos, simula tú crédito y aprende sobre los subsidios
              que el gobierno y compensar tienen para tí, solo registra tu
              perfil y recibe toda la información.
            </p>
          </div>
          <div class="index__image text-center">
            <img
              class="img-fluid"
              src="~/assets/images/imagen_index.png"
              alt=""
            />
          </div>
        </div>
        <div class="col-md-5">
          <div class="form__container p-3 mt-4 rounded">
            <div class="index__form py-3 px-5 shadow">
              <div class="form__title">
                <h2>Registra tu perfil y <br> simula tu crédito</h2>
                <p>Ingresa tus datos para iniciar una simulación</p>
              </div>
              <form >
                <FormInput id="name" title="Nombres" modeType="text"/>
                <FormInput id="last_name" title="Apellidos" modeType="text"/>
                <FormInput id="name" title="Correo electrónico" modeType="email"/>
                <FormInput id="name" title="Teléfono" modeType="text"/>
                <div class="form-button d-flex justify-content-center">
                <button class="btn btn-orange px-5 py-2 my-4"> <a class="link-button" href="/simulador-vivienda">Simular crédito</a></button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
      <div class="py-5"></div>
      <section class="mt-5">
        <div class="row">
          <div class="col-md-12 text-center">
            <h2 class="font-weight-bold">¿Qué necesitas para comprar vivienda?</h2>
            <p>Si cumples con los siguientes requisitos, avanza a simular el crédito para comprar tu casa propia</p>
          </div>
          <div class="col-md-12 py-5">
            <img src="~/assets/images/imagen_requisitos.png" alt="">
          </div>
        </div>
        <div class="row">
          <div class="col-md-6">
            <ul class="custom-list">
              <li>Ser afiliado: a la caja de compensación f​​​amiliar Compensar*.</li>
              <li>Tener conformado un hogar: conformado por una o más personas que integren el mismo núcleo familiar.</li>
              <li>Los ingresos del grupo familiar solicitante del subsidio deben ser iguales o inferiores a cuatro (4) salarios mínimos legales mensuales vigentes.</li>
              <li>No ser propietarios: ninguna de las personas que conforman el hogar pueden ser propietarias o poseedoras de vivienda, finca o lote alguno, ni haber sido adjudicatarias del Instituto de Crédito Territorial, así se haya transferido la vivienda.</li>
              <li>No haber recibido S​ubsidio de vivienda: ningún integrante del hogar puede haber recibido alguno de los siguientes subsidios.</li>
            </ul>
          </div>
          <div class="col-md-6">
            <ul class="custom-list">
              <li>Ser afiliado: a la caja de compensación f​​​amiliar Compensar*.</li>
              <li>Tener conformado un hogar: conformado por una o más personas que integren el mismo núcleo familiar.</li>
              <li>Los ingresos del grupo familiar solicitante del subsidio deben ser iguales o inferiores a cuatro (4) salarios mínimos legales mensuales vigentes.</li>
              <li>No ser propietarios: ninguna de las personas que conforman el hogar pueden ser propietarias o poseedoras de vivienda, finca o lote alguno, ni haber sido adjudicatarias del Instituto de Crédito Territorial, así se haya transferido la vivienda.</li>
              <li>No haber recibido S​ubsidio de vivienda: ningún integrante del hogar puede haber recibido alguno de los siguientes subsidios.</li>
            </ul>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      nameFormIndex: ""
    }
  },
}
</script>

<style>
.index__form {
  border-radius: 15px;
}


.index__title h1 {
  font-family: 'Roboto', sans-serif;
  font-weight: 700;
  font-size: 42px;
  text-align: center;
  line-height: 1.3;
}

.index__title p {
  padding: 1rem 0rem;
  text-align: center;
  font-weight: 300;
  font-size: 1.1rem;
  line-height: 1.8;
}

.form__title h2 {
  padding-top: 1rem;
  font-weight: 600;
  font-size: 1.625rem;
  line-height: 1.5;
  letter-spacing: 0;
}

.form__title p {
  font-weight: 300;
  font-size: 1.1rem;
  line-height: 1.8;
}

.btn-orange {
  background-color: #ff6600;
  color: white;
}

.link-button {
  color: white;
}

.link-button:hover {
  color: black;
  text-decoration: none;
}


.custom-list {
  list-style-image: url(~/assets/images/check.png);
}

.custom-list li {
  padding: .5rem;
  font-weight: 300;
  font-size: 1.1rem;
  line-height: 1.8;
}


</style>
