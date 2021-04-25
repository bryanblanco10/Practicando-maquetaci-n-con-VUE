<template>
        <!-- <div class="card">
            <div class="producto">
                <a href="#" class="share"><font-awesome-icon :icon="['fas', 'share-alt']" class="icon-share"/></a>
                <img src="../../../assets/img/product.jpg" class="imagen-producto">
            </div>

            <div class="info-product">
                <div class="name-producto">
                    <div>
                        <h1 class="title-producto">Nombre del producto</h1>
                        <span class="descuento">10%</span>
                    </div>
                    <h3 class="subtitle">Subtitulo del producto</h3>
                </div>
                <div class="description">
                    <h3>Descripción</h3>
                    <p class="text-description">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam. <a href="#">Ver más</a></p>
                </div>
                <div class="color-producto">
                    <h3 class="title">Color</h3>
                    <div class="colors">
                        <span class="color active" primary="#2175f5" color="blue"></span>
                        <span class="color" primary="#f84848" color="red"></span>
                        <span class="color" primary="#29b864" color="green"></span>
                        <span class="color" primary="#ff5521" color="orange"></span>
                        <span class="color" primary="#444" color="black"></span>
                    </div>
                </div>
                <div class="talla-producto">
                    <h3 class="title">Talla</h3>
                    <div class="tallas">
                        <span class="talla">7</span>
                        <span class="talla">8</span>
                        <span class="talla active">9</span>
                        <span class="talla">10</span>
                        <span class="talla">11</span>
                    </div>
                </div>
                <div class="precio-producto">
                    <a href="#" class="boton-carrito">
                        <font-awesome-icon :icon="['fas', 'shopping-cart']" class="icon-carrito" />
                        Agregar al
                    </a>
                    <div class="precio">
                        <font-awesome-icon :icon="['fas', 'dollar-sign']" class="icon-precio" />
                        <h1>189.99</h1>
                    </div>
                </div>
            </div>
        </div> -->
    <div class="container">
        <div class="row">
            <div class="col-lg-4 col-md-4 col-12 mb-5 card__padding">
                  <div class="card card__beneficio">
                      <div class="card-body text-center">
                          <font-awesome-icon :icon="['fas', 'user']" class="icono__beneficio mb-3" />
                          <h5 class="card__title">Ahorra tiempo</h5>
                          <p class="card__text">
                            With supporting text below as a natural lead-in to additional
                            content.
                          </p>
                      </div>
                  </div>
            </div>
        </div>
    </div>

</template>
<script>
export default{
    name: 'ModalProduct'
};
</script>