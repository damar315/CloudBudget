<template>
<div class="container5">
  <h1>Features</h1>
    <div class="row">
      <div class="col-lg-4 col-md-6">
        <div class="card border-0 text-center">
          <img src="../assets/Bg1.png" class="card-img-top" alt="bg1">
          <div class="card-body">
            <h5 class="card-title">Supports All Currencies and<br> Cards</h5>
            <p class="card-text">We support all popular currencies and is<br> fully customizable to add</p>
            <a href="" class="btn">Read More</a>
          </div>
        </div>
      </div>
      
      <div class="col-lg-4 col-md-6">
        <div class="card border-0 text-center">
          <img src="../assets/Bg2.png" class="card-img-top" alt="bg2">
          <div class="card-body">
            <h5 class="card-title">Manage your expenses on<br> the go</h5>
            <p class="card-text">You can access your account from<br> anywhere in the world on any device</p>
            <a href="" class="btn">Read More</a>
          </div>
        </div>
      </div>

      <div class="col-lg-4 col-md-6">
        <div class="card border-0 text-center">
          <img src="../assets/Bg3.png" class="card-img-top" alt="bg3">
          <div class="card-body">
            <h5 class="card-title">Cloud Budget Management<br> Software</h5>
            <p class="card-text">Our software is made so you can access<br> and manage your budget</p>
            <a href="" class="btn">Read More</a>
          </div>
        </div>
      </div>
      
    </div>
</div>
</template>

<script>
export default {
    name:'Features'
}
</script>

<style scoped>

.container5 {
  background-color: #FAFAFA;
  margin-bottom: 50px;
}

h1 {
    /* margin-left: -300px; */
    margin-top: 63px;
    padding-top: 50px;
    /* width: 1110px;
    height: 55px; */
    font-style: normal;
    font-weight: 600;
    font-size: 36px;
    line-height: 43px;
    text-align: center;
  }

.row {
  margin-top: 63px;
  margin-left: 50px;
}

.card-body {
  background-color: #ffffff;
  /* width: 250px; */
  /* height: 198px; */
  box-shadow: 0px 5px 30px rgba(0, 0, 0, 0.1);
  border-radius: 8px;
  /* margin-left: 25px;
  margin-top: -50px; */
}

.card-title {
  /* margin-top: 10px;
  margin-left: 15px; */
  /* width: 230px;
  height: 40px; */
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 22px;
  text-align: center;
}

.card-text {
  /* margin-top: 20px;
  margin-left: 15px; */
  font-style: normal;
  font-weight: normal;
  font-size: 12px;
  line-height: 150%;
  text-align: center;
}

.btn {
  /* width: 253px;
  height: 18px; */
  font-style: normal;
  font-weight: bold;
  font-size: 12px;
  line-height: 150%;
  text-align: center;
  /* margin-left: auto;
  margin-right: auto; */
  color: #ED4C5C;
}

/* desktop version
@media (min-width: 992px) {
  .card-body {
  margin-left: 30px;
  margin-top: -100px;
}

h1 {
    margin-left: 10px;
  }
}

/* tablet version */
/* @media (min-width: 768px) and (max-width: 991.98px) {
  h1 {
    margin-left: -200px;
}
.card-body {
  margin-left: 20px;
}
} */

</style>