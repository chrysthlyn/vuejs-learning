<template>
  <div id="todolist">
    <div class="container">
      <div class="row header mb-5 p-3">
        <div class="col-lg-12">
          <h2>What I Do Today?</h2>
        </div>
      </div>
      <div class="row content">
        <div class="col-lg-12">
          <div class="homework">
            <div class="row">
              <div
                v-for="myTask in task"
                v-bind:key="myTask.id"
                class="task col-lg-12 mb-2 text-start"
              >
                <div class="form-check">
                  <input
                    class="form-check-input"
                    type="checkbox"
                    value=""
                    id="flexCheckDefault"
                  />
                  <label class="form-check-label item" for="flexCheckDefault">
                    {{ myTask.taskName }}
                  </label>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";

export default {
  name: "Todolist",
  data: function () {
    return {
      task: [
        {
          id: 1,
          taskName: "Bangun Tidur",
        },
        {
          id: 2,
          taskName: "Membersihkan Rumah",
        },
        {
          id: 3,
          taskName: "Belanja Makanan",
        },
        {
          id: 4,
          taskName: "Belajar",
        },
        {
          id: 5,
          taskName: "Tidur",
        },
      ],
    };
  },
  components: {},
};
</script>

<style scoped>
.header {
  background: #1ab09c;
}

.header h2 {
  margin: 0;
}

.task .item {
  font-size: 18px;
}
</style>