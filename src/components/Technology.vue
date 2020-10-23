<template>
  <div class="container3">
    <h1>Technology</h1>
    <!-- <div class="container4"> -->
  <div class="row">
    <div class="col-lg-3 col-md-6">
      <h2>01</h2>
      <img src="../assets/ant-design_cloud-download-outline.svg" class="img1" alt="">
      <h3>Cloud Storage</h3>
      <p>Access your account from anywhere<br>in the world on any device</p>
    </div>
    <div class="col-lg-3 col-md-6">
      <h2>02</h2>
      <img src="../assets/Vector.svg" class="img2" alt="">
      <h3>Secure</h3>
      <p>All your information is stored on<br> secure cloud servers</p>
    </div>
    <div class="col-lg-3 col-md-6">
      <h2>03</h2>
      <img src="../assets/Group.svg" class="img3" alt="">
      <h3>PDF Download</h3>
      <p>Download any of your reports in<br> PDF format</p>
    </div>
     <div class="col-lg-3 col-md-6">
      <h2>04</h2>
      <img src="../assets/iwwa-file-csv.svg" class="img4" alt="">
      <h3>CSV Download</h3>
      <p>All your information is stored on<br> secure cloud servers</p>
    </div>
  </div>
</div>
  <!-- </div> -->
</template>

<script>
export default {
    name: 'Technology'
};
</script>

<style scoped>
/* .container4{
    display: grid;
    grid-template-columns: auto auto auto auto;
} */
.row{
    padding-left: 50px;
    padding-top: 52px;
    margin-left: 50px;
}
h1 {
    font-style: normal;
    font-weight: 600;
    font-size: 36px;
    line-height: 43px;
    text-align: center;
    padding-top: 50px;
}
h2{
    /* padding-left: 50px;
    padding-top: 100px; */
    font-style: normal;
    font-weight: bold;
    font-size: 100px;
    line-height: 120px;
    text-align: center;
    color: rgba(16, 16, 16, 0.08);
}
h3{
    text-align: center;
    font-size: 18px;
    /* padding-left: 50px; */
    /* padding-top: 100px; */
    font-style: normal;
    font-weight: bold;
    /* line-height: 120px; */
}p{
    font-style: normal;
    font-weight: normal;
    font-size: 12px;
    line-height: 14px;
    text-align: center;
    color: #000000;
}
.img1{
    display: block;
    margin-left: auto;
    margin-right: auto;
    height: 30%;
    margin-top:-70px;
    /* position: absolute;
    top: 59px;
    left: 110px; */

}
.img2{
    display: block;
    margin-left: auto;
    margin-right: auto;
    /* width: 50%; */
    margin-top:-70px;
}
.img3{
    display: block;
    margin-left: auto;
    margin-right: auto;
    margin-top:-70px;
    /* width: 50%; */
}
.img4{
    display: block;
    margin-left: auto;
    margin-right: auto;
    margin-top:-70px;
    /* width: 50%; */
}
</style>
