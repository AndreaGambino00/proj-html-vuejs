<template>
  <div class="smart">
      <div class="title">
          <h4>MAXCOACH AVAILABLE COURSES</h4>
          <h1>Access <span>Smart Tutoring</span> Program For Benefits</h1>
      </div>
      <div class="item">
          <div class="item1">
              <img src="../assets/home-2-image-box-01.png" alt="">
              <h3>Customize Preferences</h3>
              <p>Learnens are given the right to arrange and<br>customize their study schedule and timetable<br>based on preferences.</p>
              <h4>Start here <i class="fas fa-long-arrow-alt-right"></i> </h4>
          </div>
          <div class="item2">
              <img src="../assets/about-us-02-image-box-02.png" alt="">
              <h3>Cloud Storage</h3>
              <p>Learnens are given the right to arrange and<br>customize their study schedule and timetable<br>based on preferences.</p>
              <h4>Start here <i class="fas fa-long-arrow-alt-right"></i> </h4>
          </div>
          <div class="item3">
              <img src="../assets/home-2-image-box-03.png" alt="">
              <h3>Multimedia Channels</h3>
              <p>Learnens are given the right to arrange and<br>customize their study schedule and timetable<br>based on preferences.</p>
              <h4>Start here <i class="fas fa-long-arrow-alt-right"></i> </h4>
          </div>
        </div>
        <div class="youtube">
            <div class="testo">
                <h4>GET STARTED EFFORTLESSLY</h4>
                <h1>Enjoy Our<br><span>Companionship</span></h1>
                <p>Sneek peek into what has in store for you on our <br>
                online teaching and mentoring portal. Seek for<br>some
                hidden hints of early-bird rewards as well.</p>
                <p>Download free guidebook <i class="fas fa-long-arrow-alt-right"></i></p>
            </div>
            <img src="../assets/home-2-popup-video-poster.jpg" alt="">
            <img id="logo-you" src="../assets/icon-youtube-play.png" alt="">
        </div>
  </div>
</template>

<script>
export default {
    name:'Smart'
}
</script>

<style>
.smart {
    width: 100%;
    height: 120vh;
    background-color: white;
    padding: 50px;
}

.item {
    display: flex;
    justify-content: space-around;
}

.item1 {
    display: flex;
    flex-direction: column;
}

.item1 img {
    width: 200px;
    height: 140px;
    margin-left: 0px;
}

.item2 img {
    width: 200px;
    height: 140px;
    margin-left: 0px;
}

.item3 img {
    width: 200px;
    height: 140px;
    margin-left: 0px;
}

.testo {
    padding: 100px;
    float: right;
}

.youtube {
    padding: 50px;
}
.youtube img {
    width: 500px;
    height: 250px;
    margin-top: 80px;
}

#logo-you {
    width: 50px;
    height: 50px;
    position: relative;
    bottom: 240px;
    left: 230px;
    cursor: pointer;
}
</style>