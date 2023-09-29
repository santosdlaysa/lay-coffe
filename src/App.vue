<script setup>
import rodape from './components/rodape.vue';
import titulo from './components/titulo.vue';
import itens from './components/itens.vue';
</script>

<template>
  <div className="menu">
    <titulo></titulo>
       <itens></itens>
       <rodape></rodape>
  </div>

</template>

<style scoped>
/*menu */
.menu {
  width: 75%;
  background-color: rgba(222, 184, 135, 0.92);
  margin-left: auto;
  margin-right: auto;
  padding: 20px;
  max-width: 500px;
  border-radius: 20px;
}
</style>
