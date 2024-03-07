<template>
    <footer class="bg-dark p-3  mt-auto w-100">
        <section class="d-flex flex-column flex-md-row align-items-center justify-content-center">
            <div class="social-icons">
                <a target="_blank" href="URL_DE_FACEBOOK" class="me-4">
                    <i class="fab fa-facebook-square text-white fs-4 hoverclass"></i>
                </a>
                <a target="_blank" href="URL_DE_TWITTER" class="me-4 text-reset">
                    <i class="fab fa-twitter-square text-white fs-4 hoverclass"></i>
                </a>
                <a target="_blank" href="URL_DE_INSTAGRAM" class="me-4 text-reset">
                    <i class="fab fa-instagram-square text-white fs-4 hoverclass"></i>
                </a>
            </div>
        </section>
        <section>
            <div class="text-center text-md-start mt-5">
                <div class="row">
                    <div class="col-md-3 text-white">
                        <h6 class="fw-bold mb-4">PETFEED</h6>
                        <p>Nos dedicamos al cuido y bienestar de nuestros peluditos</p>
                    </div>
                    <div class="col-3 text-white">
                    <h6>Servicios: </h6>
                    <p>Baños medicados</p>
                    <p>Cortes de pelo</p>
                    <p>Cuido veterinario</p>
                    <p>Entrenamiento</p>
                </div>
                <div class="col-3 text-white">
                    <h6>Enlaces de Interes: </h6>
                    <p>Agendar cita (Aun no disponible)</p>
                    <p>Ayuda (Aun no disponible)</p>
                </div>
                <div class="col-3 text-white" >
                    <h6>Contactanos: </h6>
                    <p> <i class="fa-solid fa-address-book text-white fs-4 hoverclass"></i> 7722-5563</p>
                    <p><i class="fa-regular fa-envelope text-white fs-4 hoverclass"></i> somospetfeed@gma.com</p>
                    <p><i class="fa-solid fa-map-pin text-white"></i> Calle al garrobo</p>

                </div>
                </div>
              
            </div>
        </section>

    </footer>
</template>

<style scoped>
footer {
    bottom: 0;
    left: 0;
    width: 100%;
    z-index: 1000;
}

.social-icons {
    display: flex;
    align-items: center;
}

.social-icons a {
    margin-right: 1rem;
}
</style>

<script>
import '@fortawesome/fontawesome-free/css/all.css';
</script>
