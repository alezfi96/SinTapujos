<template>
<nav>
  <section>
    <a href=""> <img src="..\assets\Logo1.png" alt="" id="logo" /></a>
  </section>
  
    <ul class="menu">

            <li><a href="#"><b>Inicio</b></a></li>
            <li><a href="#"><b>Quienes Somos</b></a></li>
            <li ><a class="li2" href=""><b> Conocete y Cuidate</b></a>

                <ul class="menu1">
                    <li><a href="#"><b>Mitos y Verdades</b></a></li>
                    <li><a href="#"><b>Mitos y Verdades</b></a></li>
                    <li><a href="#"><b>Mitos y Verdades</b></a></li>
                </ul>
            </li>
            <li><a href="#"><b> Juegos</b></a></li>

            <li><a href="#"><b>Comentarios</b></a></li>
            <li><a href="#"><b>Agenda tu Cita</b></a></li>
    </ul>
</nav>
</template>

<script>
export default {
  name: "EncabezadoComp",
};

</script>
<style scoped>
.menu{
        text-align:justify;
        font-size: 20px;
        height: 5vh;
        background-color: white;
        display: flex;
        justify-content:space-evenly;
        border: 2px solid black;
    }
    .menu1{
        background-color: aquamarine;
        list-style: none;
        display: none;
        position: relative
    }
    .menu li:hover > ul{
        display: block;
        z-index: 10;
    }
    li{
        text-decoration: none;
        display: block;
    }
    a{
        text-decoration: none;
        display: block;
    }
    a:hover {
        background-color: antiquewhite;
        color:black;
    }
section {
  border: solid 1px;
  background-color: rgb(154, 239, 239);
}
img {
  display: flex;
  justify-content: flex-start;
  margin: 20px;
  width: 8%;
  height: 8%;
}
</style>