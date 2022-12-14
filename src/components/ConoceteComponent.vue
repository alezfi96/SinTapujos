<template>
    <main>
        <header>
            <nav>
                <li><a href="#">Derechos y Deberes</a></li>
                <li><a href="#">Métodos Anticonceptivos</a></li>
                <li><a href="#">Sexualidad Feminina</a></li>
                <li><a href="#">Sexualidad Masculina</a></li>
                <li><a href="#">ITS</a></li>
            </nav>
        </header>
    </main>
</template>
<script>
export default{
    name:'ConoceteComponent',
    data(){

    }
}
</script>
<style scoped>
header{
    display: flex;
}
img{

    width: 50%;
}

nav{
    display: flex;
    list-style: none;

}
li{
    display: inline-block;
    text-align:center ;
    padding: 10px 35px 10px 35px;
}
a{
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    display:block;
    text-decoration: none;
    padding: 10px;
    -webkit-transition:all 500ms ease ;
    -o-transition: all 500ms ease;
    transition:all 500ms ease ;
    
}
a:hover{
    
    background-color: aquamarine;
    border-radius: 20px;
}
</style>