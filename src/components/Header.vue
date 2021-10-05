<template>
  <header>
    <img src="../assets/dark-logo.png" alt="">

    <ul>
      <li>Home <i class="fas fa-chevron-down"></i></li>
      <li>Pages <i class="fas fa-chevron-down"></i></li>
      <li>Courses <i class="fas fa-chevron-down"></i></li>
      <li>Features <i class="fas fa-chevron-down"></i></li>
      <li>Blog <i class="fas fa-chevron-down"></i></li>
      <li>Shop <i class="fas fa-chevron-down"></i></li>
      <li><i class="far fa-user-circle"></i></li>
      <li><input id="cerca" type="text"  placeholder="Search..." ><i id="lente" class="fas fa-search"></i></li>
    </ul>
  </header>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style>
@import '~@fortawesome/fontawesome-free/css/all.min.css';
header {
  width: 100%;
  height: 10vh;
  background-color: white;
}

img {
  width: 300px;
  height: 40px;
  margin-left: 120px;
  margin-top: 20px;
  color: #3F3A64;
}

ul {
  display: flex;
  float: right;
  margin-right:100px;
 margin-top: 20px;
  }

li {
  list-style: none;
  
  margin: 10px;
  cursor: pointer;
}

#cerca {
  height: 30px;
  border: none;
  background-color: #F5F5F5 ;
}

#lente {
  color:#20AD96;
  background-color: #F5F5F5 ;
  height: 30px;
  font-size: 23px;

}
</style>