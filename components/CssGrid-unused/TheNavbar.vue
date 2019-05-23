<template>
  <div>
    <div class="topnav">
      <!-- Centered link -->
      <div class="topnav-centered">
        <a href="#home">multi.</a>
      </div>

      <!-- Left-aligned links (default) -->
      <a href="#news"><img src="~/assets/002-worldwide.png" /> EN</a>
      <a href="#contact"><input type="text" placeholder="Search.."/></a>

      <!-- Right-aligned links -->
      <div class="topnav-right">
        <a href="#search">My Account</a>
        <a href="#about"
          ><img src="~/assets/023-shopping-cart.png" /> Cart (0)
        </a>
      </div>
    </div>

    <!--second navigation bottom-->
    <div class="container" style="background-color: black; margin: -18px;">
      <nav class="navbar navbar-default" role="navigation">
        <!-- Collect the nav links, forms, and other content for toggling -->
        <div class="collapse navbar-collapse navbar-ex1-collapse">
          <ul class="nav navbar-nav">
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Projects</a></li>
            <li><a href="#">Blog</a></li>
            <li class="dropdown">
              <a href="#" class="dropdown-toggle" data-toggle="dropdown"
                >Contact <b class="caret"></b
              ></a>
              <ul class="dropdown-menu">
                <li><a href="#">Action</a></li>
                <li><a href="#">Another action</a></li>
                <li><a href="#">Something else here</a></li>
                <li><a href="#">Separated link</a></li>
                <li><a href="#">One more separated link</a></li>
              </ul>
            </li>
          </ul>
        </div>
        <!-- /.navbar-collapse -->
      </nav>
      <h1>Home</h1>
    </div>
  </div>
</template>

<script>
export default {};
</script>
<style lang="scss" scoped>
/*.inline-block{
  display: inline-block;
  background-color: white;
}*/

body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
  background-color: black;
}

.topnav {
  position: relative;
  overflow: hidden;
  background-color: #333;
}

.topnav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 20px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.topnav a.active {
  background-color: #4caf50;
  color: white;
}

.topnav-centered a {
  float: none;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.topnav-right {
  float: right;
}

/* Responsive navigation menu (for mobile devices) */
@media screen and (max-width: 600px) {
  .topnav a,
  .topnav-right {
    float: none;
    display: block;
  }

  .topnav-centered a {
    position: relative;
    top: 0;
    left: 0;
    transform: none;
  }
}

.nav {
  margin: 0px auto;
  width: 705px;

}
ul {
  list-style-type: none;
  margin: 0 auto;
  padding: 0;
}
li {
  display: inline;
  float: left;
  margin-right: 1px;
}
li a {
  display: inline-block;
  min-width: 140px;
  height: 50px;
  text-align: center;
  line-height: 50px;
  font-family: Century Gothic, Candara, Tahoma, sans-serif;
  color: #fff;
  background: #2f3036;
  text-decoration: none;
}
li:hover a {
  background: #659d32;
}
li:hover ul a {
  background: #f3f3f3;
  color: #2f3036;
  height: 40px;
  line-height: 40px;
}
li:hover ul a:hover {
  background: #659d32;
  color: #fff;
}
li ul {
  display: none;
}
li ul li {
  display: block;
  float: none;
}
li ul li a {
  width: auto;
  min-width: 100px;
  padding: 0 20px;
}
ul li a:hover + .hidden,
.hidden:hover {
  display: block;
}
.show-menu {
  font-family: Century Gothic, Candara, Tahoma, sans-serif;
  text-decoration: none;
  color: #fff;
  background: #659d32;
  text-align: center;
  padding: 10px 0;
  display: none;
}
input[type="checkbox"] {
  display: none;
}
input[type="checkbox"]:checked ~ #menu {
  display: block;
}
@media screen and (max-width: 760px) {
  ul {
    position: static;
    display: none;
  }
  li {
    margin-bottom: 1px;
  }
  ul li,
  li a {
    width: 100%;
  }
  .show-menu {
    display: block;
  }
}
</style>
