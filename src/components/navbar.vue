<template>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">PetFeed</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown"
                aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavDropdown">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Inicio</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Servicios</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                            aria-expanded="false">
                            Sobre Nosotros
                        </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">Quienes somos</a></li>
                            <li><a class="dropdown-item" href="#">Nuestra Mision</a></li>
                            <li><a class="dropdown-item" href="#">Nuestra vision</a></li>
                        </ul>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<style scoped>
nav {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    z-index: 1000;
}

.container-fluid {
    padding-right: 0;
    padding-left: 0;
}
</style>
