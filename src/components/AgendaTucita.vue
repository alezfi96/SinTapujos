<template>
<main>



    <section >
    <a href=""> <img src="@/assets/logo1.png" alt="" id="logo" /></a>
  </section>
  <nav>
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
<nav>
<div class="hola">
    
    <h1>Correo institucional </h1>

    <h2> agenda tu cita </h2>
    <div
    
    class="oe">  
    <input type="text" name="" id="" placeholder="@misena.edu.co">
 
    <input type="button" value="agendar">    
 </div>
 <h3> El agendamiendo te llagara al correo misena </h3>
</div>

   
</nav>

</main>

</template>

<script>
export default {
  name: 'AgendaTucita-',
  props: {
    msg: String
  }
}
</script>
<style >
.hola{
    border:  solid 1px;
}
h1{
    display: flex;
    justify-content: flex-start;
}
h2{
    display: flex;
    justify-content: flex-end;
}
.oe{
    display: flex;
    justify-content: flex-start;
}
section {
  border: solid 1px;
  background-color: rgb(154, 239, 239);
}
img{
  display: flex;
  justify-content: flex-start;
  margin: 20px;
  width: 8%;
  height: 8%;

}


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
    /* a{
        text-decoration: none;
        display: block;
    } */
    a:hover {
        background-color: antiquewhite;
        color:black;
    }
</style>