<template>
  <div class="header-component">
      <div class="content"></div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="less">
    .header-component{
        height: 60px;
        width: 100%;
        background-color:red;
        .content{
            min-width: 768px;
            max-width: 1440px;
            margin: 0 auto;
            height: 100%;
            background-color: aqua;
        }
    }
</style>