<template>
    <div>
      <div class="flex-container">
        <div><h4>multi.</h4>
          <p style="font-size: 14px;">But I must explain to you how all this mistaken idea of denouncing pleasure and praising pain was born and I will give you a complete account of the system, and expound the actual teachings</p>
        </div>
        <div><p class="heading">Discover</p>
          <ul style="list-style-type:none; font-size: 14px;">
            <li><a href="/about">About</a></li>
            <li><a href="/services">Services</a></li>
            <li><a href="/project">Project</a></li>
            <li><a href="/products">Products</a></li>
            <li><a href="/contact">Contact</a></li>
          </ul>
        </div>
        <div><p class="heading">Support</p>
          <ul style="list-style-type:none; font-size: 14px;">
            <li><a href="/about">About</a></li>
            <li><a href="/services">Services</a></li>
            <li><a href="/project">Project</a></li>
            <li><a href="/products">Products</a></li>
            <li><a href="/contact">Contact</a></li>
          </ul>
        </div>
        <div><o>Follow us</o>
          <div class="social">
            <a href="#news"><img src="~/assets/Facebook Icon.png"/></a>
            <a href="#news"><img src="~/assets/G+.png"/></a>
            <a href="#news"><img src="~/assets/Twitter Icon.png"/></a>
            <a href="#news"><img src="~/assets/LinkedIn Icon.png"/></a>
          </div>
        </div>
      </div>
    </div>
  </template>


  <style scoped>

    .heading{
       padding-left: 38px;
    }
    a {
      color: white;
      background-color: transparent;
      text-decoration: none;
    }

    a:hover {
      color: dodgerblue;
      background-color: transparent;
    }
    .flex-container {

      display: flex;
      flex-direction: row;
      align-items: center;

      background-color: black;
      color: white;


    }

    .flex-container > div {

      background-color: black;

      margin: 85px;
    }
    .social {
      display: flex;
    }
  </style>
