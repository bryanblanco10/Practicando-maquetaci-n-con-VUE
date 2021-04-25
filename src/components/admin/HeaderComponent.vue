<template>
	<!-- Navbar -->
	<nav class="Navbar">
		<ul>
			<li>
				<a href="#" class="">
					<font-awesome-icon :icon="['fas', 'bars']" />
				</a>
			</li>
			<li>
				<a href="#" class="notificacion">
					<font-awesome-icon :icon="['fas', 'bell']" />
					<span class="badge">10</span>
				</a>
			</li>
			<li>
				<a href="#" class="mensaje">
					<font-awesome-icon :icon="['fas', 'envelope']" />
					<span class="badge">10</span>
				</a>
			</li>
			<li>
				<a href="#" class="userright">
					<img src="../../assets/img/avatar.png" style="height: 30px; width: 30px;" alt="User">
				</a>
			</li>
		</ul>
	</nav>
</template>
<script>
export default{
	name: 'HeaderComponent'
};
</script>