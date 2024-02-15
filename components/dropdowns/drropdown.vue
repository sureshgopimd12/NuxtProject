<template>
  <div>
    <button class="colapse-button" @click="hide = !hide">dropdown</button>

    <div v-if="hide" class="content">
      <ul>
        <li>hello</li>
        <li>world</li>
        <li>hello</li>
      </ul>
    </div>
  </div>

  <div>
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ut molestie
    mi. Nam iaculis nunc quis bibendum imperdiet. Cras a nisl consequat, semper
    ex nec, porta felis. Nam eu elit et massa semper malesuada. Cras gravida
    facilisis arcu ut sagittis. Nam eleifend lectus ac consequat molestie. Duis
    eget nisl mauris. Nulla commodo fringilla ornare. Donec vel odio
    pellentesque magna dictum pellentesque. Nullam risus enim, bibendum eu
    ornare et, sollicitudin ac velit.
  </div>
</template>

<style scoped>
.colapse-button {
  padding: 2px;
  border-radius: 5px;
  border: solid;
  border-color: #7f6ebd;
  box-shadow: 0 0.125rem 0.25rem rgba(165, 163, 174, 0.3);
  color: aliceblue;
  background-color: #7f6ebd;
}

.content {
  display: block;
  position: absolute;
  z-index: 0;
  padding: 10px;
  padding-bottom: 20px;
  background-color: white;
  box-shadow: 3px 1px 3px -2px gray;
}

li {
  inset: 2px;
  list-style: none;

  padding: 2px;
}
</style>

<script setup lang="ts">
const hide = ref(false);
</script>
