<template>
  <div class="todolist">
    <h2>What I Do Today?</h2>
    <div class="homework">
      <div v-for="myTask in task" v-bind:key="myTask.id" class="task">
        <p>{{ myTask.taskName }}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Todolist",
  data: function () {
    return {
      task: [
        {
          id: 1,
          taskName: "Menyapu Rumah",
        },
        {
          id: 2,
          taskName: "Mengepel Rumah",
        },
        {
          id: 3,
          taskName: "Belanja Sayur",
        },
      ],
    };
  },
  components: {},
};
</script>
