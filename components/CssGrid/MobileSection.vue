<template>

  <div>

    <!--centered image -->
    <!--  <div class=container4>
        <a href="#news"><img src="~/assets/Group 47829.png"/></a>
      </div>-->

    <div id="container">
      <div id="left" class="col">

        <a href="#news"><img src="~/assets/GroupIcon.png"/></a>
        <p style="font-size: 20px;">Custome Software Solutions</p>
        <p style="font-size:14px;">
          Every business is unique and there is no “one-size-fits-all” when it
          comes to technology solutions that drive growth and stand you out in
          competitive market.
        </p>


        <a href="#news"><img src="~/assets/GroupIcon.png"/></a>
        <p style="font-size: 20px;">Mobile Applications</p>
        <p style="font-size:14px;">
          We like to think of the problem the app intends to solve, analyze
          mobility context and create a mobile solution meeting that need and
          satisfying user experience.
        </p>

        <a href="#news"><img src="~/assets/circle.png"/></a>
        <p style="font-size: 20px;">Mobile Applications</p>
        <p style="font-size:14px;">
          We like to think of the problem the app intends to solve, analyze
          mobility context and create a mobile solution meeting that need and
          satisfying user experience.
        </p>


      </div>
      <div id="center" class="col"><a href="#news"><img src="~/assets/Group 47829.png" class="responsive"/></a></div>
      <div id="right" class="col">

        <a href="#news"><img src="~/assets/exclude.png"/></a>
        <p style="font-size: 20px;">Design and Creative Work</p>
        <p style="font-size: 14px;">
          Design plays a key role in engaging visitors and converting them
          into customers. We focus on creating memorable interactions through
          our designs.
        </p>

        <a href="#news"><img src="~/assets/exclude.png"/></a>
        <p style="font-size: 20px;">E-Commerce Development</p>
        <p style="font-size: 14px;">
          Building intuitive, useful, secure and accessible e-Commerce
          solutions that power the transactions and digital experience is
          important to us..
        </p>

        <a href="#news"><img src="~/assets/exclude.png"/></a>
        <p style="font-size: 20px;">E-Commerce Development</p>
        <p style="font-size: 14px;">
          Building intuitive, useful, secure and accessible e-Commerce
          solutions that power the transactions and digital experience is
          important to us..
        </p>

      </div>
    </div>

  </div>
</template>


<style scoped>
  * {
    box-sizing: border-box;
  }
  #container {
    /*border: 1px solid #aaa;*/
    margin: 10px;
    padding: 10px;
    height: 100px;
  }
  .col {
    float: left;
    width: 33.33333333%;
    /* border: 1px solid #07f;*/
    padding: 0;
  }
  #left {
    text-align: left;

  }
  #center {
    text-align: center;

  }
  #right {
    text-align: left;

  }

  .responsive {
    width: 30%;
    height: auto;
  }
</style>
