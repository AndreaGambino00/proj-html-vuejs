<template>
<div class="courses">
    <div class="title">
        <h4>STIMULATED TO LEARN?</h4>
        <h1>Featured Online Courses </h1>
    </div>
    <div class="one">
        <img src="../assets/course-02.jpg" alt="">
        <div class="info">
            <h3 id="price">$40.00</h3>
            <h3>Learning to Write as a Professional <br> Author</h3>
        </div>
        <img src="../assets/mobile-bg.jpg" alt="">
       <div class="info">
            <h3 id="price">$40.00</h3>
            <h3>Learning to Write as a Professional <br> Author</h3>
        </div>
    </div>
    <div class="two">
        <img src="../assets/stock.jpg" alt="">
        <div class="info">
            <h3 id="price">$19.00</h3>
            <h3>Open Programming Courses for<br>Everyone: Python</h3>
        </div>
        <img src="../assets/stock-full.jpg" alt="">
        <div class="info">
            <h3 id="price">$26.00</h3>
            <h3>Academic Listening and Note-<br>taking</h3>
        </div>
   </div>
   <div class="three">
       <img src="../assets/course-featured.jpg" alt="">
       <div class="info">
            <h3 id="price">$39.00</h3>
            <h3>Master jQuery in a Short Period of<br>Time</h3>
        </div>
        <img src="../assets/stock-full-hd.jpg" alt="">
        <div class="info">
            <h3 id="price">$59.00</h3>
            <h3>Introduction to Javascript for<br>Beginners</h3>
        </div>
   </div>
   <div class="btn">
        <button>View all courses <i class="fas fa-long-arrow-alt-right"></i></button>
    </div>
</div>

</template>

<script>
export default {
    name:'Courses'
}
</script>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
.courses {
    width: 100%;
    height: 100vh;
    background-color: #F5F7FA;
    padding: 50px;
}
.title {
   text-align: center;
}

.info {
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.one {
    display: flex;
    align-items: center;
}
.one img {
    width: 150px;
    height: 150px;
    border-radius:100%;
    
}

.two {
    display: flex;
    align-items: center;
}
.two img {
    width: 150px;
    height: 150px;
    border-radius:100%;
}

.three {
    display: flex;
    align-items: center;
}
.three img {
    width: 150px;
    height: 150px;
    border-radius:100%;
}

.btn {
    margin-top: 50px;
    padding: 10px;
    text-align: center;
}

.btn button {
    width: 200px;
    cursor: pointer;
}

#price {
    color: #20AD96;
}
</style>