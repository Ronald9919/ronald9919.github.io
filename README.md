<!DOCTYPE html>
<html>
<head>
	<title>Mi veterinaria</title>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<!-- Agrega los enlaces a los archivos CSS y JavaScript de Bootstrap -->
	<link href="/css/bootstrap.css" rel="stylesheet">
	<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css">
</head>
<body style="background-color:lightcyan;">
	<nav class="navbar navbar-dark bg-dark" aria-label="Dark offcanvas navbar">
		<div class="container-fluid">
			<button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasNavbarDark" aria-controls="offcanvasNavbarDark" aria-label="Toggle navigation">
				<span class="navbar-toggler-icon"></span>
			</button>
			<div class="justify-content-end">
				<a class="navbar-brand fs-3" href="#"><i class="bi bi-person"></i></a>
				<a class="navbar-brand fs-3" href="#"><i class="bi bi-cart"></i></a>
				<a class="navbar-brand fs-3" href="#"><i class="bi bi-search"></i></a>
			</div>
		  <div class="offcanvas offcanvas-start text-bg-dark" tabindex="-1" id="offcanvasNavbarDark" aria-labelledby="offcanvasNavbarDarkLabel">
			<div class="offcanvas-header">
			  <h5 class="offcanvas-title fs-4" id="offcanvasNavbarDarkLabel">Perro Feliz</h5>
			  <button type="button" class="btn-close btn-close-white" data-bs-dismiss="offcanvas" aria-label="Close"></button>
			</div>
			<div class="offcanvas-body">
			  <ul class="navbar-nav justify-content-center flex-grow-1 pe-3">
				<li class="nav-item fw-bold">
				  <a class="bi bi-house nav-link fs-5 active" aria-current="page" href="#"> Home</a>
				</li>
				<li class="nav-item">
				  <a class="nav-link fs-5 bi bi-building" href="#"> Identidad</a>
				</li>
				<li class="nav-item">
				  <a class="nav-link fs-5 bi bi-lightbulb" href="#"> Filosofia</a>
				</li>
				<li class="nav-item">
				  <a class="nav-link fs-5 bi bi-clipboard" href="#"> Servicios</a>
				</li>
				<li class="nav-item">
				  <a class="nav-link fs-5 bi bi-shop" href="#"> Tienda</a>
				</li>
				<li class="nav-item">
				  <a class="nav-link fs-5 bi bi-envelope" href="#"> Contactos</a>
				 </li>
				<li class="nav-item">
				  <a class="nav-link fs-5 bi bi-three-dots" href="#"> Otros</a>
				</li>
			  </ul>	
			</div>
		  </div>
		</div> 
	</nav>
	<div class="row mt-3 ms-2 me-2">
		<div class="col col-6">
			<div class="container">
				<p class="fw-bold fs-1">
					Lorem ipsum, dolor sit amet consectetur adipisicing elit. 
					Porro quibusdam reiciendis vitae incidunt aspernatur. Impedit, 
					illum consequatur doloribus nulla harum ipsum, dolor ut corporis, 
					provident autem facilis soluta ullam. Reprehenderit.
				</p>
			</div>
		</div>
		<div class="col col-6">
			<div class="container">
				<div id="carouselExampleIndicators" class="carousel slide">
					<div class="carousel-indicators">
					  <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
					  <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
					  <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
					</div>
					<div class="carousel-inner">
					  <div class="carousel-item active">
						<img src="/img/1.jpg" class="d-block w-100" alt="">
					  </div>
					  <div class="carousel-item">
						<img src="/img/1.jpg" class="d-block w-100" alt="...">
					  </div>
					  <div class="carousel-item">
						<img src="img/1.jpg" class="d-block w-100" alt="...">
					  </div>
					</div>
					<button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
					  <span class="carousel-control-prev-icon" aria-hidden="true"></span>
					  <span class="visually-hidden">Previous</span>
					</button>
					<button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
					  <span class="carousel-control-next-icon" aria-hidden="true"></span>
					  <span class="visually-hidden">Next</span>
					</button>
				  </div>
			</div>
		</div>
	</div>
</body>
<script src="/js/bootstrap.js"></script>
</html>
