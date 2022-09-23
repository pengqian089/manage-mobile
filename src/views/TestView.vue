<template>
  <van-button type="primary" @click="clickButton">button</van-button>
</template>

<script>
import { showDialog } from 'vant';
import 'vant/es/dialog/style';
export default {
  name: "TestView",
  methods:{
    clickButton(){
      showDialog({ message: '提示' });
    }
  }
}
</script>

<style scoped>

</style>