<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->

    <HelloWorld :arr="arr1"></HelloWorld>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
  data() {
    return {
      arr1: [
        {
          img_url: "../assets/img/pic_01.jpg",
          tltle: "风景阻击手",
          num1: 10,
          num2: 80,
        },
        {
          img_url: "../assets/img/pic_01.jpg",
          tltle: "风景阻击手",
          num1: 10,
          num2: 80,
        },
        {
          img_url: "../assets/img/pic_01.jpg",
          tltle: "风景阻击手",
          num1: 10,
          num2: 80,
        },
        {
          img_url: "../assets/img/pic_01.jpg",
          tltle: "风景阻击手",
          num1: 10,
          num2: 80,
        },
        {
          img_url: "../assets/img/pic_01.jpg",
          tltle: "风景阻击手",
          num1: 10,
          num2: 80,
        },
        {
          img_url: "../assets/img/pic_01.jpg",
          tltle: "风景阻击手",
          num1: 10,
          num2: 80,
        },
      ],
    };
  },
};
</script>
