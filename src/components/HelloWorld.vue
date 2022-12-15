<template>
  <div class="hello">
    <div class="ul">
      <h4>摄影社区热门小镇</h4>
      <ul>
        {{
          arr
        }}
        <!-- <li v-for="(item)" in arr>
          <div class="left">
            <div><img src="item.img_url" alt="" /></div>
          </div>
          <div class="right">
            <h5>{{ item.tltle }}</h5>
            <span
              >成员：<em>{{ item.num1 }}</em></span
            >
            <span
              >作品：<em>{{ item.num2 }}</em></span>
          </div>
        </li> -->
        <!-- <li>
          <div class="left">
            <div><img src="../assets/img/pic_01.jpg" alt="" /></div>
          </div>
          <div class="right">
            <h5>风景阻击手</h5>
            <span>成员：<em>10</em></span>
            <span>作品：<em>80</em></span>
          </div>
        </li>
        <li>
          <div class="left">
            <div><img src="../assets/img/pic_01.jpg" alt="" /></div>
          </div>
          <div class="right">
            <h5>风景阻击手</h5>
            <span>成员：<em>10</em></span>
            <span>作品：<em>80</em></span>
          </div>
        </li>
        <li>
          <div class="left">
            <div><img src="../assets/img/pic_01.jpg" alt="" /></div>
          </div>
          <div class="right">
            <h5>风景阻击手</h5>
            <span>成员：<em>10</em></span>
            <span>作品：<em>80</em></span>
          </div>
        </li>
        <li>
          <div class="left">
            <div><img src="../assets/img/pic_01.jpg" alt="" /></div>
          </div>
          <div class="right">
            <h5>风景阻击手</h5>
            <span>成员：<em>10</em></span>
            <span>作品：<em>80</em></span>
          </div>
        </li>
        <li>
          <div class="left">
            <div><img src="../assets/img/pic_01.jpg" alt="" /></div>
          </div>
          <div class="right">
            <h5>风景阻击手</h5>
            <span>成员：<em>10</em></span>
            <span>作品：<em>80</em></span>
          </div>
        </li> -->
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    arr: Array,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
* {
  padding: 0;
  margin: 0;
}
.ul {
  width: 580px;
  height: 240px;
  border: 1px solid #000;
  padding: 10px;
}
h4 {
  margin-bottom: 15px;
}
li {
  list-style: none;
  width: 131px;
  // background-color: antiquewhite;
  display: flex;
  justify-content: space-between;
  padding: 10px;
  float: left;
  margin-right: 40px;
  margin-bottom: 25px;
  .left {
    div {
      width: 50px;
      height: 50px;
      padding: 2px;
      border: 1px solid #000;
      border-radius: 2px;
      img {
        width: 100%;
        height: 100%;
        border-radius: 2px;
        margin-right: 10px;
      }
    }
  }
  .right {
    display: flex;
    flex-direction: column;
    h5 {
      font-size: 12px;
      color: rgb(70, 116, 133);
      font-weight: normal;
      margin-bottom: 7px;
    }
    span {
      font-size: 12px;
      color: rgb(99, 98, 98);
      em {
        font-style: normal;
      }
    }
  }
}
</style>
