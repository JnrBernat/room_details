<template>
  <div class="roomDets">
    <div class="mypic">
      <img :src="img" :alt="hostelName" />
    </div>
    <div class="text">
      <h3>{{ hostelName }}</h3>
      <p>{{ text }}</p>

      <div>
        <button>Apply Now</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: ["text", "hostelName", "size", "img"],
};
</script>
<style>
.roomDets {
  max-width: 300px;
  height: 450px;
  margin-left: 20px;
  background: #eee;
  display: inline-block;
  position: relative;
  align-content: center;
  border-radius: 15px;
  margin-top: 10px;
}
.mypic {
  max-width: 280px;
  height: 200px;
  margin: 10px auto;
  background: grey;
  align-content: center;
  border-radius: 15px;
}
.alt {
  align-content: center;
  margin-top: 100px;
}
.text {
  margin-bottom: 10px;
  text-align: center;
}
h1,
h2 {
  text-align: center;
  font-weight: light;
  color: #eeee7e;
}
h3 {
  text-transform: uppercase;
  color: grey;
}
button {
  border: none;
  border-bottom: 0.5px solid #008080;
  font-weight: bold;
  margin-top: 40px;
  font-size: 1em;
  color: #008080;
}
button:hover {
  color: #ee0039;
  border-bottom: 1px solid #008080;
  font-size: 1em;
}
</style>
