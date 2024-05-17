

<script setup>
import imagen from'../assets/img/grafico.jpg'
</script>

<template>

    <div class="dos-columnas">
        <div class="contenedor-grafico" >
<img :src="imagen" alt="" srcset="">
        </div>
        <div class="control-presupuesto">

            <button class="reset-app">Reset App</button>
            <p><span>

                Presupuesto: $0
            </span></p>
            <p><span>
                Disponible: $0
            </span></p>
            <p><span>
                Gastado: $0
            </span></p>
        </div>

    </div>
</template>



<style  scoped>


</style>