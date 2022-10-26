<!--
 * @Author: I527836 cathy.chen01@sap.com
 * @Date: 2022-10-25 15:11:54
 * @LastEditors: I527836 cathy.chen01@sap.com
 * @LastEditTime: 2022-10-26 15:41:13
 * @Description: 
-->
<template>
  <div :class="[`group-34`, className || ``]">
    <div class="bubble-22"></div>
  </div>
</template>

<script>
export default {
  name: "Group34",
  props: ["className"],
};
</script>

<style lang="sass">
.group-34
  align-items: flex-start
  background: radial-gradient(50% 50% at 50% 50%, rgb(50.19, 68.33, 231.63) 0%, rgba(0, 1.59, 15.94, 0) 100%)
  border-radius: 120px
  box-shadow: inset 8.38px 16.75px 83.75px #ff0000 , inset 0px 1.68px 8.38px #ffffff94 , 0px 3.35px 67px #f700767a , 50.25px 100.5px 67px #0500ff33 , 0px 0px 16.75px #ff929221
  display: flex
  height: 240px
  left: 280px
  min-width: 240px
  position: absolute
  top: 183px

.bubble-22
  background: radial-gradient(50% 50% at 50% 50%, rgb(144,11,10) 0%, rgba(0, 1.59, 15.94, 0) 100%)
  border: 0.84px none
  border-radius: 120px
  box-shadow: inset 0px 0px 17px 0px #ff5522, inset 0px 1.68px 8.38px rgb(255 255 255 / 58%), inset 0px 3.35px 67px rgb(247 0 118 / 48%), 0px 0px 16.75px rgb(255 146 146 / 13%)
  height: 240px
  width: 240px

.group-34.group-34-1
  left: 286px
  top: 188px
</style>
