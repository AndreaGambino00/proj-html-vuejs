<template>
  <div class="number">
        <div class="trained">
            <h4>Successfully<br>trained</h4>
            <h1>1790</h1>
            <p>ENROLLED LEARNERS</p>
        </div>
        <div class="received">
            <h4>Proudly<br>Received</h4>
            <h1>19</h1>
            <p>COUNTRYWIDE AWARDS</p>
        </div>
        <div class="firmly">
            <h4>Firmly<br>Established</h4>
            <h1>24</h1>
            <p>LOCAL BRANCHES</p>
        </div>
        <div class="featured">
            <h4>Getting<br>Featured on</h4>
            <h1>1090</h1>
            <p>BLOG POSTS</p>
        </div>
      </div>
</template>

<script>
export default {
    name: 'Number'
}
</script>

<style>
.number {
    display: flex;
    justify-content: space-around;
    align-items: center;
    width: 100%;
    height: 30vh;
    background-color: white;
    padding: 30px;
}

.trained ,
.received,
.firmly,
.featured
 {
    border-left: 1px solid black;
    text-align: center;
    font-size: 17px;
    padding: 60px;
}

.trained h1 {color: #20AD96;}
.received h1 {color: #20AD96;}
.firmly h1 {color: #20AD96;}
.featured h1 {color: #20AD96;}
</style>