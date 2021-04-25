<template>
    <div>
        <header>
            <a href="#">
              <img class="imglogo" src="../../assets/logo.png">
              <label class="logo">Pidelo</label>
              <label class="textologo">Centro Comercial Virtual</label>
            </a>
              <a href="#" class="btncarrito">
                <font-awesome-icon :icon="['fas', 'shopping-cart']" />
                <span class="badge badge-pill">10</span>
              </a>
              <a href="#" class="btnregistrarse">Registrarse</a>
              <a href="#" class="btningresar">Ingresar</a>
              <a href="#" class="btnubicacion"><font-awesome-icon :icon="['fas', 'map-marker-alt']" class="iconoubicacion"/>Ubicación<font-awesome-icon :icon="['fas', 'angle-down']" class="iconoangledown"/></a>
        </header>
        <nav>
            <ul>
                <li><a class="active" href="#">Inicio</a></li>
                <li><a href="#">Categorias </a></li>
<!--                 <li><a href="#">Mi negocio</a></li>
                <li><a href="#">Mi Perfil </a></li> -->
            </ul>
        </nav>
    </div>
</template>
<script>
export default{};
</script>