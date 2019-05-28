<template>

      <div class="flex-container">
        <div class="multi" style="display:flex; flex-direction: column;"><h4>multi.</h4>
          <p style="font-size: 14px;">But I must explain to you how all this mistaken idea of denouncing pleasure and praising pain was born and I will give you a complete account of the system, and expound the actual teachings</p>
        </div>
        <div class="listed">
        <div class="discover"><p class="heading" style="font-size: 14px;">Discover</p>
          <ul style="list-style-type:none; font-size: 16px;">
            <li><a href="/about">About</a></li>
            <li><a href="/services">Services</a></li>
            <li><a href="/project">Project</a></li>
            <li><a href="/products">Products</a></li>
            <li><a href="/contact">Contact</a></li>
          </ul>
        </div>
        <div class="support"><p class="heading" style="font-size: 14px;">Support</p>
          <ul style="list-style-type:none; font-size: 16px;">
            <li><a href="/about">About</a></li>
            <li><a href="/services">Services</a></li>
            <li><a href="/project">Project</a></li>
            <li><a href="/products">Products</a></li>
            <li><a href="/contact">Contact</a></li>
          </ul>
        </div>
        </div>
        <div class="socialParent"><p >Follow us</p>
          <div class="social">
            <a href="#news"><img src="~/assets/Facebook Icon.png"/></a>
            <a href="#news"><img src="~/assets/G+.png"/></a>
            <a href="#news"><img src="~/assets/Twitter Icon.png"/></a>
            <a href="#news"><img src="~/assets/LinkedIn Icon.png"/></a>
          </div>
        </div>
      </div>
  </template>


  <style scoped>

    .heading{
       padding-left: 38px;
    }

    .listed{
      display: flex;

      margin-right: 90px;
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
      align-items: center;

    }

    .flex-container > div {
      background-color: black;
      margin: 85px;
      margin-left: 50px;
    }

    .discover {

      margin-left: 100px;
    }

    .flex-container :nth-child(1) {

    }

    .social {
      display: flex;
     /* border: 3px solid greenyellow;*/
      flex-direction: row;
    }

    .socialParent {
      display: flex;
      flex-direction: column;

    }

    .discover, .support {
     margin-right: 20px;
    }

    @media screen and (max-width: 1224px) {
      .flex-container  {
        flex-direction: column;
      }
    }

    @media screen and (max-width: 760px){

      .discover {
       margin: 0;
      }
    }
  </style>
