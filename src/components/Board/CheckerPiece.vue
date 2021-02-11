<template>
  <div class="piece absolute p-0.5 h-1/8 w-1/8 ">
    <div class="bg-white rounded-full h-full"></div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  setup() {
    return {};
  }
});
</script>

<style scoped>
.piece {
  transform: translate(200%, 100%);
}
</style>
