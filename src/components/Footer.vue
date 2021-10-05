<template>
  <div class="footer">
        <div class="adress">
            <h3>Adress</h3>
            <p>382 NE 191st St # 87394 Miami, FL 33179-3899</p>
            <p>+1(305) 547-9909 (9am - 5pm EST, Monday - Friday)</p>
            <p>support@maxcoach.com</p>
            <div class="social">
                <i class="fab fa-facebook"></i>
                <i class="fab fa-twitter"></i>
                <i class="fab fa-instagram"></i>
                <i class="fab fa-linkedin"></i>
            </div>
        </div> 
        <div class="explore">
            <h3>Explore</h3>
            <p>Start here</p>
            <p>Blog</p>
            <p>About us </p>
        </div>
        <div class="success">
            <p>Success story</p>
            <p>Courses</p>
            <p>Contact us</p>
        </div>
        <div class="information">
            <h3>Information</h3>
            <p>Membership</p>
            <p>Purchase guide</p>
            <p>Privacy policy</p>
            <p>Terms of services</p>
        </div>
  </div>
  
</template>

<script>
export default {
    name:'Footer'
}
</script>

<style>
.footer {
    width: 100%;
    height: 30vh;
    background-color: #F8F8F8;
    display: flex;
    justify-content: space-around;
    padding: 50px;
}

.social {
    font-size: 30px;
    display: flex;
    justify-content: space-around;
    cursor: pointer;
    padding: 20px;
    margin-left:-50px;
    color: #8A8A8A;
}

.success {
    margin-top: 20px;
}

.footer p {
    color: #8A8A8A ;
}
</style>