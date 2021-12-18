<template>
  <div style="margin: 20px">
    <h3>The Organization's history</h3>
    <div id="box">
      <p>The inaugural meeting was held at the elegant Jamaican Restaurant, The Door,
        located at 163-67 Baisley Blvd, Jamaica Queens NY 11434.</p>
    </div>
  </div>

</template>

<script>
export default {
name: "Histroy"
}
</script>

<style scoped>
#box{
  max-width: 900px;
  padding: 20px;
  border: 1px solid;
  border-radius: 10px;
  box-shadow: 0 0 10px black;
  margin: 20px auto;
  background-image: url("../../assets/history.png");
  background-size: cover;

}
h3, p{
  color: #800001;
  text-align: center;
}

</style>
