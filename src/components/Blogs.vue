<template>
  <div class="blogs">
      <div class="cards">
          <div class="card1">
              <img src="../assets/artis1.jpeg" alt="">
              <div class="infos">
                  <p>ARTIST</p>
                  <h5>Brush Strokes Energize Trees<br> in Paintings</h5>
              </div>
          </div>
          <div class="card2">
                <img src="../assets/artis2.jpg" alt="">
              <div class="infos">
                  <p>ARTIST</p>
                  <h5>Brush Strokes Energize Trees<br> in Paintings</h5>
              </div>
          </div>
      </div>
      <div class="infos-text">
          <p>ENJOYABLE INSIGHTS</p>
          <h2>Most Viewed <span>Best Blogs</span></h2>
          
               <li><i class="fas fa-long-arrow-alt-right"></i> Become a better Blogger: Content Planning</li>
               <li><i class="fas fa-long-arrow-alt-right"></i> Promoting Your Online Business on Pinterest</li>
               <li><i class="fas fa-long-arrow-alt-right"></i> Gamification and Game-Based Learning</li>
               <li><i class="fas fa-long-arrow-alt-right"></i> Designing an Online Course from Expert's<br>Perspective</li>
              <li><i class="fas fa-long-arrow-alt-right"></i> Why Online Courses Are the Future of Education</li>
          
      </div>
  </div>
</template>

<script>
export default {
    name:'Blogs'
}
</script>

<style>
.blogs {
    width: 100%;
    height: 50vh;
    background-color: #F5F1ED;
}

.cards {
    display: flex;
    padding: 20px;
    float: right;
    margin-right: 50px;
}

.card1{
    display: flex;
    flex-direction: column;
}

.card1 img {
    width: 240px;
    height: 200px;
}

.card2 img {
    width: 240px;
    height: 200px;
}

.infos {
    background-color: white;
    width: 240px;
    padding: 10px;
    margin-left: 120px;
}

.infos-text {
    padding: 50px;
 margin-left: 190px ;
}
</style>