<script setup></script>

<template>
  <div>
    <div class="row">
        <div class="col">
            <span class="text-nav">COINFEEVER</span> 
        </div>
        <div class="col">
            <button class="btn-nav">Share</button>
        </div>
    </div>
    <div class="row">
      <div class="col-7 cont">
        <div class="container">
            <div class="row">
          <div class="row">
            <p>
              <span class="title">Spend your crypto </span> <br />
              <span class="subtitle">in a new way.</span> 
            </p>
          </div>
          <div>
            <p class="paragrah">
              Get yourself an ultimate crypto card & payment <br /> solution whithin
              decentralized network. <br /> Forget about KYC forever
            </p>
          </div>
        </div>
        <div class="row mt-3">
          <div class="col-6">
            <input class="input shadow" type="text" placeholder="Your email" />
          </div>
          <div class="col-6">
            <button class="btn-my shadow">Preorder</button>
          </div>
        </div>
        </div>
      </div>
      <div class="col-5 ">
        <lottie-player
          autoplay
          loop
          mode="normal"
          src="https://assets6.lottiefiles.com/packages/lf20_O1b0iWuPju.json"
          style="width: 300px"
          class="container-img"
        >
        </lottie-player>
      </div>
    </div>
  </div>
</template>

<style scoped>
.text-nav{
    position: absolute;
    top: 0;
    left: 0;
    margin-left: 30px;
    margin-top: 20px;
    color: #8B61CB;
    font-weight: bold;
    
}

.btn-nav{
    position: absolute;
    width: 80px;
    right: 0;
    top: 0;
    margin-right: 50px;
    margin-top: 20px;
    background-color: #4722DD;
    text-align: center;
    color: #fff;
    border-radius: 20px;
    height: 35px;
    border:none;
    font-size: 14px;

}
.cont{
    margin-top: 10%;
}
.container-img{
    display: block;
    margin-left: auto;
    margin-right: auto;
    margin-top: 10%;
}

.title{
    color:#100C34;
    font-size: 70px;
    font-weight: bold;
}

.subtitle{
    color: #904EF9;
    font-size: 35px;
    font-weight: bold;
}

.paragrah{
    color: grey;
    font-size: 20px;
    text-align: left;
}

.input{
    border-radius: 15px;
    border: 1px solid #fff;
    height: 45px;
    font-size: 14;
    width: 100%;
    padding-left: 20px;
}

.input:active{
    border: 1px solid #fff !important;
}

.input:focus{
    outline: none;
    color: gray;
}

.input::placeholder{
    color: gray;
    font-size: 14px;
    text-align: left;
    margin-left: 10px;
    align-items: center;
}

.btn-my{
    width: 55%;
    background-color: #100C32;
    text-align: center;
    color: #fff;
    border-radius: 20px;
    height: 45px;
}
</style>
