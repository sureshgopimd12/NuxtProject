<template>
  <button class="primary" @click="hide = !hide">click here</button>

  <div v-if="hide" class="overlay" @click="changethe">
    <div class="content">
      <div class="inner-content">
        she should keep in mind, there is nothing I do better than revenge
        <button  class="primary" @click="hide =false"> close</button>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue';
const hide = ref(false);

const changethe = (event)=>{

  console.log(event.target)
  console.log(event.currentTarget )
  console.log(event.eventPhase)
  console.log("here you go ")
}

</script>

<style scoped>
.overlay {
  position: fixed;
  z-index: 9998;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.5);
}

.content {
  position: relative;
  width: 400px;
  z-index: 9999;
  margin: 215px auto;
  padding: 20px 30px;
  background-color: #fff;
  border-color: red;
  animation: scale 0.5s ease; 
  border-style: solid;
}

.primary {
  background-color: #eae8fd;
  display: inline-block;
  width: auto;
  color: #7367f0;
  padding: 5px;
  border-radius: 4px;
}

@keyframes scale {
  from { transform: scale(0); }
  to { transform: scale(1); } 
}
</style>
