<template>
  <div id="app">
   <nav class="navbar navbar-expand-lg fixed-top ">
   <a class="navbar-brand" href="#">Home</a>
   <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
     <span class="navbar-toggler-icon"></span>
   </button>
   
<div class="collapse navbar-collapse " id="navbarSupportedContent">
     <ul class="navbar-nav mr-4">
       
       <li class="nav-item">
         <a class="nav-link" href="#">About</a>
       </li>
       <li class="nav-item">
         <a class="nav-link " href="#">Portfolio</a>
       </li>
       <li class="nav-item">
         <a class="nav-link " href="#">Team</a>
       </li>
       <li class="nav-item">
         <a class="nav-link " href="#">Post</a>
       </li>
       <li class="nav-item">
         <a class="nav-link " href="#">Contact</a>
       </li>
     </ul>
     
   </div>
   </nav>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
.navbar{
 background:#F97300;
}
.nav-link , .navbar-brand{
 color: #f4f4f4;
 cursor: pointer;
}
.nav-link{
 margin-right: 1em !important;
}
.nav-link:hover{
 background: #f4f4f4;
 color: #f97300;
}
.navbar-collapse{
 justify-content: flex-end;
}
.navbar-toggler{
  background:#fff !important;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
