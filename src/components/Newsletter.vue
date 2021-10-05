<template>
  <div class="newsletter">
      <h1>Subscribe <span>Newsletter</span></h1>
      <p>Enter your email adress to register to our newsletter subscription<br>delivered on a regular basis</p>
      <div class="input-news">
          <input id="enter" type="text" placeholder="Enter your email">
          <button id="sub">Subscribe</button>
      </div>
  </div>
</template>

<script>
export default {
    name: 'Newsletter'
}
</script>

<style>
.newsletter {
    width: 100%;
    height: 30vh;
    text-align: center;
    padding: 60px;
}

#enter {
    width: 300px;
    height: 40px;
    border: none;
    background-color:#F5F5F5 ;
}

#sub {
    height: 40px;
    border-radius: 0px;
    padding: 10px;
}

span {
    color: #20AD96;
}
</style>