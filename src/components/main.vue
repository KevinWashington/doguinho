<template>
    <section>
        <div class="row text-center text-md-start mb-5">
            <div class="d-flex flex-column align-items-center col-md-6 mt-3 herotext">
                <h2 class="mt-5 fs-5">Dê identidade para seu negócio</h2>
                <div>
                    <h1 style="font-weight: 900;" class="display-2 fw-bold">Agência de Marketing</h1>
                    <p class="text-muted mt-4">Potencialize sua presença digital com estratégias de marketing personalizadas</p>
                </div>
                <a href="" class="btn btn-primary mt-5 w-50 p-3 fw-bold">Marcar reunião <i class="mdi mdi-arrow-right-thick"></i> </a>
            </div>
            <div class="col-md-6">
                <img src="../assets/logo.png" alt="" class="m-auto float-md-end">
            </div>
        </div>
    </section>
</template>
<script>
export default {
    name: "Section"
    
}
</script>
<style>
    .nav-item .nav-link{
        color: #CA65C3 !important;
    }
    @media screen and (max-width: 425px) {
        .herotext{
            height: calc(100vh - 100px);
            justify-content: space-evenly;
        }
    }
</style>