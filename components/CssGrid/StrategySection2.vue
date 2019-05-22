<template>



  <div class="center">

    <img src="~/assets/undraw_content_vbqo.png" class="responsive"/>

    <div class="features">
      <div class="grids">
        <a href="#news"><img src="~/assets/GroupIcon.png"/></a>
        <p style="font-size: 20px;">But I must explain to you how all</p>
        <p style="font-size:14px;">
          The quick, brown fox jumps over a <br> lazy dog. DJs flock by when MTV ax.
        </p>
      </div>

      <div class="grids">
        <a href="#news"><img src="~/assets/circle.png"/></a>
        <p style="font-size: 20px; ">But I must explain to you how all</p>
        <p style="font-size:14px">
          But I must explain to you how all <br> this mistaken idea of denouncing pleasure
        </p>

      </div>

      <div class="grids">
        <a href="#news"><img src="~/assets/GroupIcon.png"/></a>
        <p style="font-size: 20px;">Bt I must explain to you how all</p>
        <p style="font-size:14px;">
          The quick, brown fox jumps over a <br> lazy dog. DJs flock by when MTV ax.
        </p>
      </div>

      <div class="grids">
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
  .center {
    margin: auto;
    width: 80%;
    padding: 80px;
    display:grid ;
    grid-template-columns: repeat(2, 1fr);
    grid-gap:1em;
  }

  .responsive {
    width: 90%;
    height: auto;
  }


  .features {
    display:grid ;
    grid-template-columns: repeat(2, 1fr);
  }
</style>
