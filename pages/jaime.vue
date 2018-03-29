<template>
<div class="grid">
<div>Inicio</div>
<div>Inicio</div>
<div>Inicio</div>
<div>Inicio</div>
</div>
</template>
<style>
div.grid{
    display: grid;
    padding: 1em;
    background-color: aquamarine;
    grid-template-columns: 1fr 2fr;
    grid-gap: 1em;
}
div.grid div{
    background-color: red;
    padding: 2em;
}
</style>
