<template>
    <div class="content-1 content" :style="writeImgUrl">
        <p class="commont-p">{{title}}</p>
        <i class="iconfont">&#xe702;</i>
    </div>
</template>
<script>
export default {
  data () {
    return {
      writeImgUrl: {
        backgroundImage: 'url(' + require('../../assets/contentImg/write.jpg') + ')',
        backgroundSize: '200px 200px',
        opacity: '0.9'
      },
      title: '我的创作'
    }
  }
}
</script>

<style>
.content-1 {
    overflow: hidden;
    margin-left: 45px;
    margin-right: 50px;
    margin-bottom: 50px;
    float: left;
    width: 300px;
    height: 400px;
    text-align: center;
}

</style>
