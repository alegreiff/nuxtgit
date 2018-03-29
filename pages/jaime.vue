<template>
<div class="grid">
<div>Inicio</div>
<div>Inicio</div>
<div>Inicio</div>
<div>Inicio</div>
<div>Inicio</div>
<div>FIN</div>
</div>
</template>
<style>
div.grid{
    display: grid;
    padding: 1em;
    background-color: rgb(35, 81, 230);
    grid-template-columns: 1fr 2fr;
    grid-gap: 1em;
}
div.grid div{
    background-color: rgb(43, 101, 245);
    padding: 2em;
    color: aliceblue;
    font-size: 1.6em;
}
</style>
