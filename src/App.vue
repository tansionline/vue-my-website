<template>
  <div id="app">
    <div id="nav">
      <nav class="navbar navbar-expand-lg fixed-top row">
      <router-link id="home" tag="li" class="col" class-active="active" to="/">Selcuk Tatar</router-link> 
      <router-link id="about" tag="li" class="col" class-active="active" to="/about">About</router-link>
      <router-link id="work" tag="li" class="col" class-active="active" to="/work">Project</router-link>
      <router-link id="contact" tag="li" class="col" class-active="active" to="/contact">Contact</router-link> 
    <router-view />
    </nav>
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style>
 @import url('https://fonts.googleapis.com/css2?family=Merriweather:ital,wght@1,900&display=swap');
 @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP&display=swap');

  nav {
    margin-top: 3%;
  }

  nav a:link, nav a:visited { 
    text-decoration: none;
    color:rgb(21, 49, 56)
  }

  nav a:hover {
    color: rgb(64, 126, 35);
  }

  #home {
    font-family: 'Merriweather', serif;
    margin-left: 3%;
    font-size: 25px;
  }

  #about, #work, #contact {
    float: right;
    display: inline-grid;
    grid-template-columns: 50px 50px 50px; 
  }

</style>