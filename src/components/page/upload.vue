<style media="screen">
  div > h1 {
    margin-bottom: 20px;
  }
</style>
<!--
用这个在线的服务器来测试 post：http://putsreq.com/Qwfn5G5QzVzIkZSMEIB8/inspect
-->
<template>
    <div>
      <h1>使用 iView 自带的文件上传组件，方便快捷...</h1>
      <Upload
          multiple
          type="drag"
          action="http://putsreq.com/Qwfn5G5QzVzIkZSMEIB8">
          <div style="padding: 20px 0">
              <Icon type="ios-cloud-upload" size="52" style="color: #3399ff"></Icon>
              <p>点击或将文件拖拽到这里上传</p>
          </div>
      </Upload>
    </div>
</template>
<script>
    export default {

    }
</script>
