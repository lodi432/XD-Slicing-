<template>

  <div id="wrap">
    <div id="left">
      <img src="~/assets/undraw_in_sync_xwsa.png" class="responsive"/>
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

  #left, #right {
    padding: 20px;
    margin:150px;
  }



  @media screen and (max-width: 1200px) {
    .left {
      display: block;

    }

    .responsive {
      width: 380px;
      margin-right: -200px;
    }

  }

</style>
