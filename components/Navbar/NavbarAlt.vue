<template>
  <div>


  <div class="topnav">

    <!-- Centered link -->
    <div class="topnav-centered">
      <a href="#home">multi.</a>
    </div>

    <!-- Left-aligned links (default) -->
    <a href="#news"><img src="~/assets/002-worldwide.png" /> EN</a>
    <a href="#contact"> <input type="text" placeholder="Search.."/></a>

    <!-- Right-aligned links -->
    <div class="topnav-right">
      <a href="#search">My Account</a>
      <a href="#about"
      ><img src="~/assets/023-shopping-cart.png" /> Cart (0)
      </a>
    </div>

  </div>
  <div>
  </div>


  </div>
</template>


<style>
  body{
    margin:0px;
  }
  .topnav {
    position: relative;
    background-color: black;
    overflow: hidden;

  }

  /* Style the links inside the navigation bar */
  .topnav a {
    float: left;
    color: #f2f2f2;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    font-size: 17px;
  }

  /* Change the color of links on hover */
  .topnav a:hover {
    background-color: #ddd;
    color: black;
  }

  /* Add a color to the active/current link */
  .topnav a.active {
    background-color: #4CAF50;
    color: white;
  }

  /* Centered section inside the top navigation */
  .topnav-centered a {
    float: none;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }

  /* Right-aligned section inside the top navigation */
  .topnav-right {
    float: right;
  }

  /* Responsive navigation menu */
  @media screen and (max-width: 600px) {

    .topnav a, .topnav-right {
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
</style>
