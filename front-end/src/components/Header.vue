<template>
  <div id="Header">
    <div class="top-left-edition">
      <span style="color: #157477; font-weight: bold">
        <i class="el-icon-user" style="font-size: 23px"></i
        >广州大学，LinLiang
      </span>
    </div>
    <div id="word">
      <h1>{{ msg }}</h1>
    </div>
  </div>
</template>
<script>
export default {
  name: "Header",
  data() {
    return {
      msg: "基于YOLOv5的电路板缺陷检测",
      activeIndex: "1",
    };
  },
  methods: {},
};
</script>
<style scoped>
#Header {
  padding: 30px 100px 0 100px;
  width: 90%;
  margin: 10px auto;
}

#word {
  margin-left: 15%;
  margin-top: -35px;
  margin-bottom: 37px;
  height: 60px;
  line-height: 3.2em;
  letter-spacing: 8px;
}

h1 {
  /*text-align: center;*/
  color: #157477;
  letter-spacing: 30px;
  font-size: 2.3em;
}

.el-menu-demo {
  width: 80%;
  margin: 0px auto;
  padding: 0px auto;
}

.top-left-edition span i {
  float: left;
  margin-right: 10px;
}

i,
input,
label {
  vertical-align: middle;
}

i {
  border: 0;
  display: block;
  cursor: pointer;
}

.top-left-edition span {
  float: right;
  font-size: 13px;
  color: #999999;
  line-height: 24px;
  margin-right: 40px;
}
</style>


