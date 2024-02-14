<template>
<div >

<button class="colapse-button" @click="hide=!hide"  >collapse the content</button>



<Transition   :duration="550">
  <div v-if="hide"  class=" content ">
  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras felis felis, malesuada in nulla id, sollicitudin dictum augue. Vestibulum condimentum, dui at consectetur consequat, magna turpis rhoncus sem, ut eleifend massa quam et nunc. Vivamus non accumsan nisi, vel dignissim diam.
</div>
</Transition>

</div>


</template>


<style scoped>


/* we will explain what these classes do next! */
.v-enter-active,
.v-leave-active {
  transition: opacity 0.5s ease;
}

.v-enter-from,
.v-leave-to {
  opacity: 0;
}


.colapse-button{
padding: 2px;
border-radius: 5px;
border: solid;
border-color: #7f6ebd;
box-shadow:0 0.125rem 0.25rem rgba(165,163,174,.3);
color: aliceblue;
background-color: #7f6ebd;
}



.content{
  border: black;
  padding: 8px;
  border-style: solid;
  margin: 6px;
}
</style>

<script setup lang="ts">
const hide =ref(true)
</script>
