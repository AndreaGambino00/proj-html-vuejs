<template>
  <div class="learn">
      <div class="title">
          <h4>GREAT WORDS ABOUT MAXCOACH</h4>
          <h1>Our <span>top Learners'</span> verbatim</h1>
      </div>
      <div class="box">
          <div class="box1">
              <h4>It's a choice of quality for people with special<br>needs</h4>
              <p>I'm a very strict person so i require everythink to be <br>organized and neat. Then,i'll be able to make thinks<br>right and shine. MaxCoach guys just got me.</p>
              <div class="info1">
                  <img id="testimonial" src="../assets/testimonial-avata-03.jpg" alt="">
                  <h4>FLORENCE THEMES</h4>
                  <p>/Multimedia Admin</p>
              </div>
          </div>
          <div class="box2">
              <h4>It's a choice of quality for people with special<br>needs</h4>
              <p>I'm a very strict person so i require everythink to be <br>organized and neat. Then,i'll be able to make thinks<br>right and shine. MaxCoach guys just got me.</p>
              <div class="info1">
                  <img id="testimonial" src="../assets/testimonial-avata-02.jpg" alt="">
                  <h4>MINA HOLLACE</h4>
                  <p>/Multimedia Admin</p>
              </div>
          </div>
          <div class="box1">
              <h4>It's a choice of quality for people with special<br>needs</h4>
              <p>I'm a very strict person so i require everythink to be <br>organized and neat. Then,i'll be able to make thinks<br>right and shine. MaxCoach guys just got me.</p>
              <div class="info1">
                  <img id="testimonial" src="../assets/testimonial-avata-01.jpg" alt="">
                  <h4>MADLEY PONDOR</h4>
                  <p>/Multimedia Admin</p>
              </div>
          </div>
      </div>
      <div class="slider">
          <div class="point1"></div>
          <div class="point2"></div>
          <div class="point3"></div>
          <div class="point4"></div>
      </div>
      <div class="certification">
          <h3>Start today for getting <span>Online Certification</span></h3>
          <h1>You can be your own guiding star with our help!</h1>
          <button>Get started now</button>
      </div>
  </div>
</template>

<script>
export default {
    name: 'Learn'
}
</script>

<style>
.learn {
    width: 100%;
    height: 90vh;
    background-color: #F8F8F8;
    padding: 50px;
}

.box {
    display: flex;
    justify-content: space-around;
    margin-top: 40px;
}

.info1 {
    display: flex;
    flex-direction: column;
}

.box1 , .box2 {
    width: 400px;
    height: 290px;
    background-color: white;
    padding: 10px;
}

.box1 {
    filter: brightness(50%);
}

#testimonial {
    display: flex;
    height: 100px;
    width: 100px;
    border-radius: 60px;
    margin-left: 0px;
}

.slider {
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
    padding: 30px;
    
}

.point1 {
    width: 12px;
    height: 12px;
    background-color: black;
    border-radius: 50px;
    
}

.point2,
.point3,
.point4 {
    width: 10px;
    height: 10px;
    background-color: gray;
    border-radius: 50px;
    margin-left: 10px;
}

.certification {
    text-align: center;
    padding: 30px;
}

.certification img {
    width: 200px;
    float: left;
}


</style>