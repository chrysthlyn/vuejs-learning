<template>
  <div class="form-check">
    <input
      class="form-check-input"
      type="checkbox"
      value=""
      id="flexCheckDefault"
    />
    <label
      class="form-check-label item"
      v-bind:class="{ 'item-completed': myTask.isDone }"
      for="flexCheckDefault"
    >
      {{ myTask.taskName }}
    </label>
  </div>
</template>

<script>
export default {
  name: "myTask",
  props: ["myTask"],
};
</script>

<style scoped>
</style>