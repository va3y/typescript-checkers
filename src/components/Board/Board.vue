<template>
  <div class="h-64 w-64 flex m-auto">
    <div class="relative w-full h-full board">
      <checker-piece />
      <checker-piece />
      <checker-piece />
      <checker-piece />
      <checker-piece />
      <checker-piece />
      <checker-piece />
      <checker-piece />
      <checker-piece />
      <checker-piece />
      <checker-piece />
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import CheckerPiece from "./CheckerPiece.vue";

export default defineComponent({
  components: { CheckerPiece },
  setup() {
    return {};
  }
});
</script>

<style scoped>
.board {
  background: url("~@/assets/board.svg") no-repeat;
}
</style>
