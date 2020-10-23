<template>
  <div class="container6">
    <div class="row">
      <div id="text1" class="col-lg-6 col-md-6">
        <h4 class="overview-info"> Easy to Use Cloud Budget Management Software</h4>
        <p>Our software is made so you can access and manage your budget and expenses online at any time from any device. It provides detailed income and expense reports with graphs so you can easilly see your spending patterns and budget at a glance. Read below to find out more.</p>
        <button type="button" class="btn btn-link">Learn More</button>
      </div>
      <div id="video" class="col-lg-6 col-md-6">
        <img src="../assets/Video_bg.png" alt="meetings" class="overview-img">
        <img src="../assets/Play Button.svg" alt="" class="play">
      </div>
    </div>
  </div>
      
</template>

<script>
export default {
    name: 'CloudInfo'
}
</script>

<style scoped>

.container6{
  display: flex;
  flex-direction: column;
  align-items: stretch;
  margin-bottom: 100px;
  margin-left: 50px;
}
#text1{
  display: block;
}
.overview-info {
  margin-top: 140px;
  font-size: 36px;
  font-weight: 600;
  text-align: left;
  margin-left: 50px;
}
p{
  margin-top: 24px;
  margin-left: 50px;
  font-size: 14px;
  font-weight: 400;
  text-align:justify;
}
.overview-info a{
  margin-left: -40px;
  font-size: 14px;
  font-weight: 400;
  color: #ED4C5C;
}
.overview-img{
  justify-content: center;
  border-radius: 15px;
  margin-top: 94px;
  border-color: #C4C4C4, 100%;
}
.btn {
  margin-top: 10px;
  display: block;
  margin-left: 40px;
  margin-right: auto;
}
.play{
  margin-top: -200px;
  display: block;
  margin-left: -20px;
  margin-right: auto;
}


</style>