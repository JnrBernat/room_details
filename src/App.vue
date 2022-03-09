<template>
  <div class="logo">
    <a href="hit.ac.zw">
      <img src="../src/assets/hitlogo.png" alt="hit logo" />
    </a>
  </div>
  <h2>Rooms providing conjussive environments for study</h2>
  <Hostel
    size="7.5"
    hostelName="Hostel 1"
    text="h1 room details here.....Lorem ipsum dolor sit amet consectetur adipisicing elit.Lorem ipsum dolor sit amet consectetur adipisicing elit."
    img="../src/assets/1.jpg"
  />
  <Hostel
    size="5.0"
    hostelName="Hostel 2"
    text="h2 room details here.....Lorem ipsum dolor sit amet consectetur adipisicing elit.Lorem ipsum dolor sit amet consectetur adipisicing elit. "
    img="../src/assets/1.jpg"
  />
  <Hostel
    size="5.0"
    hostelName="Hostel 3"
    text="h3 room details here.....Lorem ipsum dolor sit amet consectetur adipisicing elitLorem ipsum dolor sit amet consectetur adipisicing elit.."
    img="../src/assets/1.jpg"
  />
  <Hostel
    size="5.0"
    hostelName="Hostel 4"
    text="h4 room details here.....Lorem ipsum dolor sit amet consectetur adipisicing elit.Lorem ipsum dolor sit amet consectetur adipisicing elit."
    img="../src/assets/1.jpg"
  />

  <div class="bottom">
    <i>..All packages come with free wifi and breakfast</i>
  </div>
</template>

<script>
import Hostel from "./components/Hostel.vue";

export default {
  name: "App",

  components: {
    Hostel,
  },
  data() {
    return {
      hostelName: "",
      text: "",
      size: "",
      img: "",
    };
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
body {
  background: #008080;
}
.bottom {
  margin-top: 20px;
  color: #eeee7e;
}

.logo > i {
  margin-left: 20px;
}
</style>
