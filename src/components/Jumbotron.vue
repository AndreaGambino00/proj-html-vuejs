<template>
  <div class="jumbotron">
      <div class="text">
          <h1>Distant learning for <br> further expansion</h1>
          <p>Learning is a life-long journey that in fact we never find <br>the terminate stop. Stop searching, enjoy the process.</p>
          <button><i class="fas fa-download"></i> Download free guide</button>
          <p>Have questions? <span>Get Free Sample</span><i class="fas fa-long-arrow-alt-right"></i></p>
          <img id="ragazza" src="../assets/ragazza.jpg" alt="">
        </div>
      <div class="loghi">
            <img src="../assets/client-logo-01.png" alt="">
            <img src="../assets/client-logo-02.png" alt="">
            <img src="../assets/client-logo-03.png" alt="">
            <img src="../assets/client-logo-04.png" alt="">
            <img src="../assets/client-logo-05.png" alt="">
            <img src="../assets/client-logo-06.png" alt="">
        </div>
    </div>
</template>

<script>
export default {
 name:'Jumbotron'
}
</script>

<style>
.jumbotron {
    position: relative;
    width: 100%;
    height: 65vh;
    background-color: #FFFFFF;
}

.text {
    padding: 100px;
    margin-left: 100px;
    
}

button {
    height: 40px;
    color: white ;
    background-color: #20AD96;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    padding: 10px;
}

#ragazza{
    position: absolute;
    top: 40px;
    right: 300px;
    border-radius: 100%;
    float: right;
    width: 400px;
    height: 300px;
}

.loghi {
    display: flex;
}

.loghi img {
    width: 100px;
    height: 50px;
    
}


</style>