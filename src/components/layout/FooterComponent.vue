<template>
	<footer id="footer">
		<div class="wrap">
			<div id="menu_footer">
				<h5>Categorías</h5>
				<ul>
					<li><a href="#">Restaurantes</a></li>
					<li><a href="#">Licores</a></li>
					<li><a href="#">Farmacias</a></li>
					<li><a href="#">Tecnologia</a></li>
					<li><a href="#">Juguterias</a></li>
				</ul>
			</div>
			<div id="info">
				<h5>Información de interés</h5>
				<ul>
					<li><a href="#">Terminos y condiciones</a></li>
					<li><a href="#">Politica de tratamiento de datos</a></li>
					<li><a href="#">Registra tú negocio</a></li>
				</ul>
			</div>
			<div id="info2">
				<h5>Descarga la App</h5>
				<p id="apps">
					<a href="#">
						<img class="ios-store" src="../../assets/img/ios_store-badge.png">
					</a>
					<a href="#">
						<img class="play-store" src="../../assets/img/play-store.png">
					</a>
				</p>
				<h5>Siguenos en</h5>
				<div class="redes-sociales">
					<li class="facebook">
						<a href="#">
							<font-awesome-icon :icon="['fab', 'facebook']" class="iconofab"/>
						</a>
					</li>
					<li class="instagram">
						<a href="#">
							<font-awesome-icon :icon="['fab', 'instagram']" class="iconoinst"/>
						</a>
					</li>
					<li class="youtube">
						<a href="#">
							<font-awesome-icon :icon="['fab', 'youtube']" class="iconoyout"/>
						</a>
					</li>
				</div>
			</div>
		</div>
	</footer>
</template>
<script>
export default{};
</script>