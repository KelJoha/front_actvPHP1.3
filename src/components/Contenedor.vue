<template>
    <div class="mi_primer_diseño">
        <h4>Mi primer parrafo =)(=</h4>
        <p>...Este es mi primer parrafó...
            ¿Por qué programar puede ser feliz?
            Programar puede ser una actividad creativa que te permite resolver problemas.
            Programar puede ser una actividad que te permite experimentar la felicidad al hacer felices a los demás.
            Programar puede ser una actividad que te permite sentirte como un superhéroe.
            Programar puede ser una actividad que te permite enfocarte en tu crecimiento y ser mejor cada día. </p>

    </div>


    <div class="mb-3">
        <label for="exampleFormControlInput1" class="form-label">Nombre y Apellido</label>
        <input type="text" class="form-control" id="TextoNombreYApellido" placeholder="Coloque su nombre y apellido">
    </div>

    <div class="mb-3">
        <label for="exampleFormControlInput1" class="form-label">Cédula</label>
        <input type="number" class="form-control" id="NumCedula" placeholder="Coloque su CC">
    </div>


    <div class="mb-3">
        <label for="exampleFormControlTextarea1" class="form-label">Feedback</label>
        <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
    </div>

</template>


<script setup>
</script>



<style scope>
.mi_primer_diseño {
    background-color: rgb(165, 116, 42);
    width: 400px;
    height: 300px;
    position: relative;
    padding: 14px;
    margin: 4px;
    top: 50%;
    left: 50%;
}

.mb-3 {
    position: relative;
}
</style>
