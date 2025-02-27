<template>
    <div class="mi_primer_diseño">

        <p>Este es mi primer parrafo: ewsd bnfgv x cklz mv</p>

    </div>


    <div class="mb-3">
        <label for="exampleFormControlInput1" class="form-label">Nombre y Apellido</label>
        <input type="text" class="form-control" id="TextoNombreYApellido" placeholder="Coloque su nombre y apellido">
    </div>

    <div class="mb-3">
        <label for="exampleFormControlInput1" class="form-label">Cedula</label>
        <input type="number" class="form-control" id="NumCedula" placeholder="Coloque su CC">
    </div>


    <div class="mb-3">
        <label for="exampleFormControlTextarea1" class="form-label">Cedula</label>
        <textarea class="form-control" id="exampleFormControlTextarea1" rows="numero"></textarea>
    </div>

    <div class="mb-3">
        <label for="exampleFormControlTextarea1" class="form-label">Example textarea</label>
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

.mb-3{
    position:relative;
}
</style>
