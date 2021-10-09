<template>
  <div class="template">
    <div class="temp_top">
      <div class="temp_top_left"></div>
      <div class="temp_top_right"></div>
    </div>
    <div class="temp_center_left"></div>
    <div class="temp_center_right"></div>
    <div class="temp_center_center"></div>
    <div class="temp_center_bottom">
      <div class="bot_left_1"></div>
      <div class="bot_left_2"></div>
      <div class="bot_left_3"></div>
      <div class="bot_left_4"></div>
    </div>
    <div class="temp_bottom_first">
      <div class="temp_bot_1"></div>
      <div class="temp_bot_2"></div>
      <div class="temp_bot_3"></div>
      <div class="temp_bot_4"></div>
      <div class="temp_bot_5"></div>
      <div class="temp_bot_6"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Template',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.template {
  width: 100% !important;
}
.temp_top {
  background-color: blanchedalmond;
  color: black;   
  height: 100px;
  border: 1px solid;
  margin: 0 !important;
  overflow: hidden;
}
.temp_top_left {
  background-color: grey;
  color: black;
  border: 1px solid;
  height: 78px !important;
  width: 250px !important;
  margin: 10px 0 10px 50px !important;
  padding: 0 0 0 0 !important;
  display: block;
  float: left;
}
.temp_top_right {
  background-color: blue;
  color: black;
  border: 1px solid;
  display: block;
  float: right;
  height: 78px !important;
  width: 250px !important;
  margin: 10px 50px 10px 10px !important;
}
.temp_center_left {
  background-color: blue;
  color: black;
  border: 1px solid;  
  display: block;
  margin-top: 10px !important;
  margin-right: 40px !important;
  width: 350px !important;
  height: 700px !important;
  float: left;
}
.temp_center_right {
  background-color: blue;
  color: black;
  border: 1px solid;
  display: block;
  margin: 10px 0 0 0 !important;
  padding: 0 0 0 0 !important;
  width: 350px !important;
  height: 700px !important;
  float: right;
}
.temp_center_center {
  background-color: burlywood;
  color: black;
  border: 1px solid;
  padding: 0 0 0 0 !important;
  margin: 10px 0 0 400px !important;
  width: 700px !important;
  height: 600px !important;
}
.temp_center_bottom {
  background-color: blue;
  color: black;
  border: 1px solid;
  margin: 10px 350px 0 400px !important;
  height: 80px !important;
  width: 700px !important;
}
.bot_left_1 {
  background-color: burlywood;
  float: left;
  color: black;
  border: 1px solid;
  width: 55px !important;
  height: 55px !important;
  margin: 10px 0 0 250px !important;
}
.bot_left_2 {
  background-color: black;
  float: left;
  color: black;
  border: 1px solid;
  width: 55px !important;
  height: 55px !important;
  margin: 10px 0 0 10px !important;
}
.bot_left_3 {
  background-color: blanchedalmond;
  float: left;
  color: black;
  border: 1px solid;
  width: 55px !important;
  height: 55px !important;
  margin: 10px 0 0 10px !important;
}
.bot_left_4 {
  background-color: green;
  float: left;
  color: black;
  border: 1px solid;
  width: 55px !important;
  height: 55px !important;
  margin: 10px 0 0 10px !important;
}
.temp_bottom_first {
  color: black;
  border: 1px solid;
  height: 100px !important;
  margin-top: 25px !important;
  background-color: blanchedalmond;
}
.temp_bot_1 {
  color: black;
  border: 1px solid;
  height: 99px !important;
  width: 180px !important;
  background-color: red;
  float: left;
}
.temp_bot_2 {
  color: black;
  border: 1px solid;
  height: 70px !important;
  width: 250px !important;
  margin: 10px 10px 10px 30px !important;
  background-color: red;
  float: left;
}
.temp_bot_3 {
  color: black;
  border: 1px solid;
  height: 70px !important;
  width: 250px !important;
  margin: 10px 10px 10px 30px !important;
  background-color: red;
  float: left;
}
.temp_bot_4 {
  color: black;
  border: 1px solid;
  height: 70px !important;
  width: 250px !important;
  margin: 10px 10px 10px 30px !important;
  background-color: red;
  float: left;
}
.temp_bot_5 {
  color: black;
  border: 1px solid;
  height: 70px !important;
  width: 250px !important;
  margin: 10px 10px 10px 30px !important;
  background-color: red;
  float: left;
}
.temp_bot_6 {
  color: black;
  border: 1px solid;
  height: 70px !important;
  width: 109px !important;
  margin: 10px 0 10px 40px !important;
  background-color: red;
  float: left;
}
</style>
