<template>
<nav class="container">
    <a href="#home">Home</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
  
</template>
<script>
export default {
    
}
</script>

<style scoped>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  padding: 0;
  font-family: 'Quicksand', sans-serif;
  color: #555;
}

.container {
  padding-left: 15%;
  padding-right: 15%;
  margin: auto;
}


nav {
  height: 70px;
  line-height: 80px;
text-align: center;
  
  width: 100%;
  z-index: 999;
  background: #fff;

  box-shadow: 0px 6px 20px rgba(0, 0, 0, 0.2);
  
}

nav a {
  display: inline-block;
  text-decoration: none;
  margin-right: 45px;
  color: #555;
  font-size: 1em;
  font-weight: 900;
  
}
nav :hover {
  border-bottom: 1px solid #6c1cff;
 border-bottom-color: #6c1cff;
  
}



@import url(https://fonts.googleapis.com/css?family=Open+Sans);

body{
  background: #f2f2f2;
  font-family: 'Open Sans', sans-serif;
}

.search {
  width: 100%;
  position: relative;
  display: flex;
}

.searchTerm {
  width: 100%;
  border: 1px solid #555;
  border-right: none;
  padding: 25px;
  height: 20px;
  border-radius: 5px 0 0 5px;
  outline: none;
  color: #9DBFAF;
}

.searchTerm:focus{
  color: #00B4CC;
}



/*Resize the wrap to see the search bar change!*/
.wrap{
  width: 85%;
  position: absolute;
  top: px;
  left: 50%;
  transform: translate(-50%, -50%);
  margin-bottom: 40px;
}


</style>