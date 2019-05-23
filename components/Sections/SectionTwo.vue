<template>
  <div id="flexi">
    <div id="left">
      <img src="~/assets/undraw_content_vbqo.png" id="responsive"/>
    </div>
    <div id="right">
      <div id="block1">
        <a href="#news"><img src="~/assets/GroupIcon.png"/></a>
        <p style="font-size: 20px;">But I must explain to you how all</p>
        <p style="font-size:14px;">
          The quick, brown fox jumps over a <br> lazy dog. DJs flock by when MTV ax.
        </p>
      </div>
      <div id="block2">
        <a href="#news"><img src="~/assets/circle.png"/></a>
        <p style="font-size: 20px; ">But I must explain to you how all</p>
        <p style="font-size:14px">
          But I must explain to you how all <br> this mistaken idea of denouncing pleasure
        </p>
      </div>
      <div id="block3">
        <a href="#news"><img src="~/assets/GroupIcon.png"/></a>
        <p style="font-size: 20px;">Bt I must explain to you how all</p>
        <p style="font-size:14px;">
          The quick, brown fox jumps over a <br> lazy dog. DJs flock by when MTV ax.
        </p>
      </div>
      <div id="block4">
        <a href="#news"><img src="~/assets/circle.png"/></a>
        <p style="font-size: 20px;">But I must explain to you how all</p>
        <p style="font-size:14px">
          But I must explain to you how all <br> this mistaken idea of denouncing
        </p>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  #flexi{
    display:flex;
    height: 625px;
    border: 3px solid lightgray;
    justify-content: center;
    align-items: center;
  }

  #left{
    height: 380px ;
    width: 510px;
  }

  #right{
    /*  border: 3px solid deepskyblue;*/
    display:flex;
    height: 380px ;
    width: 620px;
    justify-content: center;
    flex-direction: column;
    flex-wrap: wrap;
    margin:150px;
  }

  #block2{
    margin-left: 40px;
  }

  #block3{
    order: -1;
  }

  #block4{
    margin-left: 40px;
  }

  #responsive {
    width: 90%;
    height: auto;
  }

  @media screen and (max-width: 760px) {

    #flexi{
      border: none;

    }

    #right {
      flex-direction: row;
      flex-wrap: wrap;
      margin:  90px 0px 0px 0px ;
      width: 100%;
      position: absolute;
      }

    #left{
    }

    #block2{
      margin-left: 0px;
    }

    #block4{
      margin-left: 0px;
    }

    #responsive {
      width: 50%;
      margin-left: 100px;
      margin-top: -150px;
      height: auto;
    }
  }
</style>
