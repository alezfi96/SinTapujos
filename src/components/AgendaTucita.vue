<template>
<main>

<nav>
<div class="hola">
    
    <h1>Correo institucional </h1>

    <h2> agenda tu cita </h2>
    <div
    
    class="oe">  
    <input type="text" name="" id="" value="@misena.edu.co">
 
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
</style>