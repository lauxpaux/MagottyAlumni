<template>
  <div id="box">
    <b-card no-body class="overflow-hidden" style="max-width: 1200px;">
      <b-row no-gutters>
        <b-col md="5">
          <b-card-img :src="require('@/assets/unnamed.jpg')" alt="Card Image" class="rounded-0" style="max-width: 520px"></b-card-img>
        </b-col>
        <b-col md="6">
          <b-card-body id="title" class="align-middle">
            <b-card-title><h1>About Maggotty High Alumni Association – US northern Region</h1></b-card-title>
            <hr>
            <b-card-text id="context">
              <p style="font-size: 15px">
                The inaugural meeting was held at the elegant Jamaican Restaurant,
                The Door, located at 163-67 Baisley Blvd, Jamaica Queens NY 11434.
              </p>
              <a href="/history" style="color: #880001">READ MORE</a>
            </b-card-text>
          </b-card-body>
        </b-col>
      </b-row>
    </b-card>
  </div>
</template>

<script>
export default {
  data(){
    return{

    }
  }
}
</script>

<style scoped>
  #box{
    max-width: 1200px;
    margin: 0 auto;
  }
  #title{
    color: #800001;
  }
  #context{
    color: black;
    margin: 0 auto;
    font-size: 20px;
  }
</style>
