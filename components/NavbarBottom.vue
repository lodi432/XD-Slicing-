<template>
  <div>
    <!--second navigation bottom-->
    <div class="container" style="background-color: black; margin: -18px; margin: -21px;">
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

    color: #fff;

    text-decoration: none;
  }
  li:hover a {
    background: gray;
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


  //Responsive stuff for navigation ! Revisit !!!!


 /* @media screen and (max-width: 760px) {
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
  }*/
</style>
