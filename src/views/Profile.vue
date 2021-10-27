<template>
  <div class="profile">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-6">
          <div class="d-flex text-start">
            <div class="flex-shrink-0">
              <img
                src="../assets/photo-profile.png"
                alt="Photo Profile"
                class="user-pic"
              />
            </div>
            <div class="flex-grow-1 ms-3">
              <h5>{{ firstName }} {{ lastName }}</h5>
              <p>{{ bioProfile }}</p>
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
  name: "Profile",
  data: function () {
    return {
      firstName: "Boas",
      lastName: "Christian",
      bioProfile: "Hi, my hobbies include breakfast, lunch and dinner.",
    };
  },
  components: {},
};
</script>

<style scoped>
.user-pic {
  border-radius: 200%;
  height: 80px;
  width: 80px;
}
</style>
