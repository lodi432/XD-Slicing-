<template>

  <div id="wrap">
    <div id="left">s
      <img src="~/assets/undraw_in_sync_xwsa.png" id="responsive"/>
    </div>
    <div id="right">
      <a href="#news"><img src="~/assets/GroupIcon.png"/></a>
      <p style="font-size: 20px;">Mihedrin interdum lorem eleifend orci </p>
      <a href="#news"><img src="~/assets/group 47820.png"/></a>
      <p style="font-size: 20px; ">Duis vestibulum elit vel neque pharetra vulputate.</p>
      <p style="font-size:14px">
        But I must explain to you how all.
      </p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  #wrap {
    display: flex;
    width: 100%;
    height: 690px;
    justify-content: center;
    align-items: center;
  }

   #right {
    padding: 20px;
    margin:150px;
  }

  @media screen and (max-width: 760px){
    #right{
      flex-direction: row;
      flex-wrap: wrap;
      margin:  140px 0px 0px 0px ;

      position: absolute;
    }

    #responsive {
      width: 30%;
      margin-left: 120px;
      margin-top: -30px;
      height: auto;
    }
  }
</style>
