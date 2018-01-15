<template>
    <nav class="navbar navbar-expand-lg fixed-top">
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo01" aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
            <a class="navbar-brand" href="#">
                <img src="/assets/brand/bootstrap-solid.svg" width="30" height="30" class="d-inline-block align-top" alt="">
                Ibatido
            </a>
            <ul class="navbar-nav mr-auto mt-2 mt-lg-0"></ul>
            <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Inicio <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Productos</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Retos</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Contacto</a>
                </li>
            </ul>
            <form class="form-inline my-2 my-lg-0">
                <input class="form-control mr-sm-2" type="search" placeholder="Buscar..." aria-label="Search">
            </form>
            <ul class="navbar-nav">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Iniciar sesion <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Registrarse</a>
                </li>
            </ul>
            <ul class="navbar-nav">
                <li class="nav-item">
                    <a class="nav-link" href="#">
                        <i class="material-icons">shopping_basket</i>
                        <span class="badge">0</span>
                    </a>
                </li>
            </ul>
        </div>
    </nav>
</template>


<script>
export default {
  name:"hola"
}
</script>

<style scoped>
    @import url("https://fonts.googleapis.com/icon?family=Material+Icons");

    nav{
        background: #2c3e50;
        padding: 25px;
    }

    nav a {
        color: #fff;
    }

    nav a:hover{
        color: #16a085;
    }
</style>
