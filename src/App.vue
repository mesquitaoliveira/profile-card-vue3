<template>
  <div class="container">
        <div class="cover-photo">
            <img src="./assets/profile.png" class="profile">
        </div>
        <div class="profile-name">Jonh Doe</div>
        <p class="about">
            <i class="fab fab fa-ethereum"></i>
            Ethereum developer and <br>
            <i class="fab fab fas fa-dice-d6"></i> Web 3.0  
        developer  </p>
        <button class="msg-btn">Messege</button>
        <button class="follow-btn">Following</button>
        <div>
            <i class="fab fab fa-hive"></i>
            <i class="fab fa-linkedin"></i>
            <i class="fab fa-youtube"></i>
            <i class="fab fa-github"></i>        
        </div>
    </div>
</template>

<script> 
  export default {
  name: 'App'
} 
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,200;0,300;0,400;0 de,500;1,500&display=swap');

body{
    font-family: 'Montserrat', sans-serif;
    background-color: #015863;
}
.container{
    user-select: none;
    margin: 100px auto;
    background: #161926;
    color:#b3b8cd;
    border-radius: 5px;
    width: 350px;
    text-align: center;
}
.cover-photo{
    background: url(./assets/background.jpeg);
    height: 160px;
    border-radius: 5px 5px 0 0;
}
.container img{
    position:center;
    height: auto;
    width:auto;
    max-width: 120px; 
    max-height: 120px;
    overflow:hidden;
}
.profile{
    height: 120px;
    width: 120px;
    border-radius: 50%;
    margin: 93px 0 0 -175px;
    border: 1px solid #03bfbc;
    padding: 5px;
    background: #0e1430;
}
.profile-name{
    font-size:25px;
    font-weight:bold;
    margin:27px 0 0 120px;
}
.about{
    margin-top: 35px;
    line-height: 21px;
}
button{
    margin: 10px 0 40px 0;
}
.msg-btn, .follow-btn{
    background:#03bfbc;
    border:1px solid #03bfbc;
    padding: 10px 25px;
    color: #231e39;
    border-radius:3px;
    font-family: Montserrat, sans-serif;
    cursor:pointer;
}
.msg-btn{
    margin-left: 10px;
    background:transparent;
    color:#02899c;
}
.msg-btn:hover{
    color:#231e39;
    background:#03bfbc;
    transition: 0.5s;
}
.follow-btn{
    margin-left: 10px;
    background:transparent;
    color:#02899c;
}
.follow-btn:hover{
    color:#231e39;
    background:#03bfbc;
    transition: 0.5s;
}
.container i{
    padding-left: 20px;
    font-size: 20px;
    margin-bottom: 20px;
    cursor:pointer;
    transition: .5s;
}
.container i:hover{
    color:#03bfbc;

}
</style>