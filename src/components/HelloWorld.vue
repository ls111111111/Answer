<template>
    <div>//放一个div，红色就没了
    <h1>学习Vue</h1>
    <h1>{{ msg }}</h1>
    <button @click='ffff'>按钮11</button>
    <Test title="ggdqac"></Test>
    <Movie title='成长' pic='https://img2.doubanio.com/view/photo/s_ratio_poster/public/p2842327103.webp'
    score='8.9' name='坏小孩'>
    </Movie>
    </div>
</template>
 
<script>
import Movie from './Movie.vue'
import Test from './Test.vue'

export default {
  components:{
    Movie,
    Test    //注册完就可以在该文件中使用
  },
  // name: 'HelloWorld',
  data: function(){
    return{
    msg: "qqqq"
   }
  },
  methods:{
    ffff:function(){
      alert("dwawqqwqw")
    }
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
