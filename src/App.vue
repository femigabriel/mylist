<template>
  <div id="app">
    <header>
      <h4>What are you looking for?</h4>
      <div class="company-logo"></div>
      <nav class="navbar">
        <ul class="nav-items">
          <li class="nav-item"><a href="#" class="nav-link">Home</a></li>
          <li class="nav-item"><a href="#" class="nav-link">Explre</a></li>
          <li class="nav-item"><a href="#" class="nav-link">Listing</a></li>
          <li class="nav-item"><a href="#" class="nav-link">More</a></li>
        </ul>
      </nav>
      <div class="sign-in">
        <h4>Sign in or Register</h4>
      </div>
      <div class="menu-toggle">
        <button>Add a Listing</button>
      </div>
    </header>
  </div>
  <Submenu />
  <Search />
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <div class="card">
  <Card
    username=" Liman Restaurant"
    tag="Innovative cooking, paired with fine wines"
    phone="+44 20 1324 21"
    address="60 Penton Street"
    mark=""
    logo="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/msclogo-150x150.png"
    image="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/photo-1508006728353-6ecef00dcbb8-768x512.jpg"
  />


  <Card
    username="Typing Room"
    tag="European fare and notable wines."
    phone="+44 20 1324 21"
    address="Patriot Square"
    logo="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/DjUcpuxI-150x150.png"
    image="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/photo-1533777857889-4be7c70b33f7.jpg"
  />

  <Card
    username="The Active People"
    tag="Edwardian picture house, screening mainstream films"
    phone="+44 20 8467 123"
    address="27 Old Gloucester Street"
    logo="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/boatt_1x-150x150.jpg"
    image="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/photo-1485967249725-2d0b975fa8a2-768x512.jpg"
  />

  <Card
    username="Museum Of London"
    tag="Edwardian picture house, screening mainstream films"
    phone="+44 20 8467 123"
    address="150 London Wall"
    logo="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/lgoom-150x150.jpg"
    image="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/tunnel-the-archaeology-of-crossrail-exhibition-at-museum-of-london-docklands_262158-768x513.jpg"
  />

  <Card
    username="Electric Cinema"
    tag="Edwardian picture house, screening mainstream films"
    phone="+44 20 8467 123"
    address="191 Portobello Road"
    logo="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/logo60-1-150x150.jpg"
    image="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/4.2.2_dolbycinema_innovativeseating_promo4V2-768x328.jpg"
  />

  <Card
    username="The Lebury"
    tag="Innovative cooking, paired with fine wines"
    phone="+44 20 1324 21"
    address="Carlton Hill"
    logo="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/screenshot_2015-11-24_14.16.17-150x150.png"
    image="https://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/photo-1519671282429-b44660ead0a7-768x512.jpg"
  />

  <Card
    username="  Ministry Of Sound"
    tag="Flagship all-night club with dance and house music brand."
    phone="+44 20 1324 21"
    address="103 Gaunt Street"
    logo="https://ml0xnijd7w94.i.optimole.com/w:auto/h:auto/q:75/http://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/uk-ministry.jpg"
    image="http://main.mylistingtheme.com/wp-content/uploads/sites/6/2019/11/whereslugo-410902-unsplash.jpg"
  />
  </div>
</template>

<script>
import Submenu from "./components/Submenu";
import Search from "./components/Search";
import Card from "./components/Card";

export default {
  name: "App",
  components: {
    Submenu,
    Search,
    Card,
  },
};
</script>

<style scoped>
@media screen and (min-width: 800px) {
  .container {
    margin: 1em 2em;
  }
}
*,
*::before,
*::after {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
.card {
  display: grid;
   grid-template-columns: repeat(3, 1fr);
  gap: px;
 }


li {
  list-style: none;
}
a {
  text-decoration: none;
}

body {
  font-family: "Raleway", sans-serif;
  font-size: 1rem;
}

header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: #242429;
  padding: 1rem 2rem;
  height: 80px;
}
.company-logo {
  font-size: 2.5rem;
  color: #fff;
}
.nav-items {
  display: flex;
}
.nav-item {
  margin: 0 2rem;
}
.sign-in h4 {
  color: #999;
  font-size: 14px;
}
.nav-link {
  font-size: 1.1rem;

  position: relative;
  color: #fff;
  cursor: pointer;
  transform-origin: bottom right;
  transition: all 0.25s;
}
.nav-link:hover {
  transition: all 0.25s;
  cursor: pointer;
}

h4 {
  color: #fff;
  font-weight: 700;
}
button {
  background: #fff;
  color: blue;
  padding: 20px 30px;
  border-radius: 10px;
}
</style>

