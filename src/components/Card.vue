<template>
  <section>
    <div class="main-background">
      <div class="background">
        <img :src="image" alt="" />
      </div>

      <div class="background-label">
        <div class="logo">
          <img :src="logo" alt="" />
        </div>
        <h4>{{ username }}</h4>
        <h6>{{ tag }}</h6>
        <ul class="lf-contact">
          <li>{{ phone }}</li>
          <li>{{ address }}</li>
        </ul>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  props: ["username", "tag", "phone", "address", "image", "logo", "mark"],

  data() {
    return {};
  },
};
</script>

<style scoped>
section {

}

.background img {
  width: 90%;
  height: 25%;
  border-radius: 10px;
}
.background-label {
  background: cornsilk;
  width: 90%;
}

.background-label h4 {
  font-weight: 700;
  font-size: 14px;
  color: #242429;
}

h6 {
  font-size: 14px;
  font-weight: 100;
  color: #242429;
}
.logo img {
  width: 13%;
  border-radius: 50%;
}

ol,
ul {
  list-style-type: none;
  padding: 5px;
  transition: 0.5s;
}
li {
  
  font-weight: 500;
}
</style>