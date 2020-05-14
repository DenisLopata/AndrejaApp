<template>
  <div class="hello2">
    <h1>Andrea - bazašica</h1>
    <h2>2016. - 2020.</h2>
     <carousel :per-page="2" :navigationEnabled="true" :autoplay="true" >
    <slide>
      <img height="70%" width="70%" src="https://previews.123rf.com/images/antonioguillem/antonioguillem1801/antonioguillem180100315/93750709-two-excited-coworkers-celebrating-achievement-giving-five-at-office.jpg">      
    </slide>
    <slide>
      <img height="70%" width="70%" src="https://previews.123rf.com/images/fizkes/fizkes1908/fizkes190800372/128089120-wide-horizontal-image-multicultural-cheerful-businesspeople-sitting-together-at-meeting-giving-high-.jpg">      
    </slide>
    <slide>
      <img height="70%" width="70%" src="https://previews.123rf.com/images/chagin/chagin1507/chagin150700016/42150246-business-team-showing-unity-with-their-hands-together.jpg">      
    </slide>
    <slide>
      <img height="70%" width="70%" src="https://previews.123rf.com/images/chagin/chagin1301/chagin130100021/17516759-successful-business-woman-sitting-with-her-team-at-office.jpg">      
    </slide>
  </carousel>
  <div>
    <iframe id="existing-iframe-example"
          width="640" height="360"
          src="https://www.youtube.com/embed/JkK8g6FMEXE?autoplay=1&mute=0&enablejsapi=1"
          frameborder="0"
          style="border: solid 4px #37474F"
          ></iframe>
  </div>
  </div>
</template>

<script>

export default {
  name: 'CarouselComponent'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
