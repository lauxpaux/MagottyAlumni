<template>
  <div id="box">
    <div class="w-100" id="colorTop"></div>
    <div class="w-100" id="colorBottom">
      <p id="AA"><b>©2021 by Maggotty High Alumni Association US Northern Region. All Right Reserved <br>
      site made by The Mondays</b></p>
    </div>
    <div style="z-index: 1;">
      <div class="mx-auto" style="width: 250px;">Centered element
      <b-container>
        <b-row>


          <b-col sm="6">
            Quick Links
            <p><a href="/q&a">FAQs</a></p>
            <p><a href="/history">History</a></p>
            <p><a href="/events">Events</a></p>
            <p><a href="/officer">Officers</a></p>
            <p><a href="/donate">Donate</a></p>

            <p></p>
          </b-col>
        </b-row>
        <br><br><br>

      </b-container>
      </div>
    </div>

  </div>
</template>

<script>
export default {
name: "Bottom"
}
</script>

<style type="text/css" scoped>
  #box{
    max-width: 1200px;
    margin: 0 auto;
    position: relative;
  }

  p{
    margin: 0;
    padding: 0;
  }

  #AA{
    color: #800001;
    font-size: 18px;
    text-align: center;
  }

  a{
    color: black;
  }

  #colorTop{
    background-color: #CEC094;
    height: 25px;
    position: absolute;
    z-index: 0;
  }

  #colorBottom{
    background-color: #CEC094;
    height: 50px;
    position: absolute;
    bottom: 0;
    z-index: 0;
  }



</style>
