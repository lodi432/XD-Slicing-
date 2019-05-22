<template>
    <div class="flexi">

      <div class="left">
      <img src="~/assets/undraw_content_vbqo.png" class="responsive"/>
      </div>

      <div class="right">
        <div class="block1">
        <a href="#news"><img src="~/assets/GroupIcon.png"/></a>
        <p style="font-size: 20px;">But I must explain to you how all</p>
        <p style="font-size:14px;">
          The quick, brown fox jumps over a <br> lazy dog. DJs flock by when MTV ax.
        </p>
        </div>

        <div class="block2">
        <a href="#news"><img src="~/assets/circle.png"/></a>
        <p style="font-size: 20px; ">But I must explain to you how all</p>
        <p style="font-size:14px">
          But I must explain to you how all <br> this mistaken idea of denouncing pleasure
        </p>
        </div>

        <div class="block3">
        <a href="#news"><img src="~/assets/GroupIcon.png"/></a>
        <p style="font-size: 20px;">Bt I must explain to you how all</p>
        <p style="font-size:14px;">
          The quick, brown fox jumps over a <br> lazy dog. DJs flock by when MTV ax.
        </p>
        </div>

        <div class="block4">
        <a href="#news"><img src="~/assets/circle.png"/></a>
        <p style="font-size: 20px;">But I must explain to you how all</p>
        <p style="font-size:14px">
          But I must explain to you how all <br> this mistaken idea of denouncing
        </p>
          </div>
      </div>
    </div>
</template>

<style scoped>

  .flexi{
    display:flex;
    height: 625px;
/*    border: 3px solid green;*/
    justify-content: center;
    align-items: center;

  }

  .left{
    /*border: 3px solid deepskyblue;*/
    height: 380px ;
    width: 510px;

  }

  .right{
  /*  border: 3px solid deepskyblue;*/
    display:flex;
    height: 380px ;
    width: 620px;
    justify-content: center;
    flex-direction: column;
    flex-wrap: wrap;
    margin:150px;
  }


   .block1{

   }

  .block2{
    margin-left: 40px;
  }
  .block3{

    order: -1;

  }

  .block4{
    margin-left: 40px;

  }

  .responsive {
    width: 93%;
    height: auto;
  }

  @media screen and (max-width: 1300px) {
    .flexi {
      flex-direction: column;
    }

   /* .block3 {
      flex-direction: column;
  }

    .block4 {
      flex-direction: column;
    }*/
  }


</style>
