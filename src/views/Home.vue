<template>
    <div>
    <img src="@/assets/me.png" />
    <br>
    <h1 id="home-header">🖐️ Hi, I am Selcuk</h1>
       <p>Junior Frontend Developer</p>
       
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
 @import url('https://fonts.googleapis.com/css2?family=Merriweather:ital,wght@1,900&display=swap');
 @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP&display=swap');
    
    div {
        background-image: url(../assets/home.svg);
        background-repeat: no-repeat ;
        background-position: center;
        object-fit: contain;
        padding: 50px;
    }

   img {
       margin-top: 5%;
       margin-left: auto;
       margin-right: auto;
       display: block;
   }

   h1 {
        text-align: center;
        font-size: 30px;
        font-family: 'Merriweather', serif;
        color: rgb(172, 70, 70);
   }

   p {
       text-align: center;
       font-size: 20px;
       font-family: 'Noto Sans JP', sans-serif;
       color: rgb(15, 131, 73);
   }
</style>