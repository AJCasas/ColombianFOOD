<template>
  <div>
      <section class="bienvenido">
  
</section>
      <div class="container">
      <div class="row">
        <div class="col-md-6">
          <a href="https://www.larepublica.co/cocina"><img src="../../assets/img/cocina.jpg" alt="..." class="img-thumbnail"></a>
        </div>
        <div class="col-md-6">
          <a href="https://www.eltiempo.com/noticias/cocina-colombiana"><img src="../../assets/img/cocina2.jpg" alt="..." class="img-thumbnail"></a>
        </div>
      </div>
    </div>
    <!--AQUÍ COMIENZA EL FOOTER-->
    <section class="footer">
      <div class="container">
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'Noticias',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.bienvenido{
    background: url("../../assets/img/fondo-movil2.jpg");
    background-size: cover;
    height: 100vh;
    overflow: hidden;
}



@media (min-width: 768px) { 
    
    .bienvenido{
        background: url("../../assets/img/fondo2.jpg");
        background-size: cover;
        height: 100vh;
        overflow: hidden;
    }
}
</style>
