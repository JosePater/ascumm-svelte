<script>
  import { page } from '$app/stores';
  import logo from '$lib/images/logo.png';
</script>

<header>
	<nav class="navbar navbar-expand-lg bg-success"  data-bs-theme="dark">
	<!-- <nav class="navbar bg-primary"> -->
		<div class="container-fluid">
		  <a class="navbar-brand" href="/">ASCUMM</a>
		  <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
			<span class="navbar-toggler-icon"></span>
		  </button>
		  <div class="collapse navbar-collapse" id="navbarNavDropdown">
			<ul class="navbar-nav">
			  <li class="nav-item">
				<a class="nav-link active" aria-current="page" href="/">Inicio</a>
			  </li>
			  <li class="nav-item">
				<a class="nav-link active" href="/nosotros">Nosotros</a>
			  </li>
			  <li class="nav-item dropdown">
				<a class="nav-link dropdown-toggle active" href="/" role="button" data-bs-toggle="dropdown" aria-expanded="false">
				  Proyectos
				</a>
				<ul class="dropdown-menu  bg-success">
				  <li><a class="dropdown-item" href="/">Agricultura</a></li>
				  <li><a class="dropdown-item" href="/">Acuicultura</a></li>
				  <li><a class="dropdown-item" href="/">Más proyectos</a></li>
				</ul>
			  </li>
			</ul>
		  </div>
		</div>
	  </nav>
</header>

<style>
	a {
		font-weight: bold;
	}
</style>
