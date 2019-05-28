<template>

  <div>
    <div class="a">
      <h2>Features</h2>
      <a href="#news"><img src="~/assets/path 28175.png"/></a>
    </div>
    <div class="center">

      <div class="flexi">
        <a href="#news"><img src="~/assets/coffe.png" class="responsive"/></a>
        <p style="font-size: 20px;">The quickys, brown fox jumps over a lazy dog DJs flock</p>
        <p style="font-size:14px;">
          The quick, brown fox jumps over a lazy dog. DJs flock by when MTV ax quiz prog. Junk MTV quiz
        </p>
        <p style="font-size: 13px;">
          May,18,2018 | Inspiration
        </p>
      </div>
      <div class="flexi">
        <a href="#news"><img src="~/assets/donut.png" class="responsive"/></a>
        <p style="font-size: 20px; ">The quick, brown fox jumps over a lazy</p>
        <p style="font-size:14px">
          The quick, brown fox jumps over a lazy dog. DJs flock by when MTV ax quiz prog. Junk MTV quiz.
        </p>
        <p style="font-size: 13px;">
          May,18,2018 | Inspiration
        </p>
      </div>
      <div class="flexi">
        <a href="#news"><img src="~/assets/deathNote.png" class="responsive"/></a>
        <p style="font-size: 20px;">The quick, brown fox jumps over a lazy dog DJs flock</p>
        <p style="font-size: 14px;">
          The quick, brown fox jumps over a lazy dog. DJs flock by when MTV ax quiz prog. Junk MTV quiz.
        </p>
        <p style="font-size: 13px;">
          May,18,2018 | Inspiration
        </p>
      </div>
    </div>
  </div>
</template>
<style lang="scss" scoped>
  div.a {
    text-align: center;
  }
  .center {
    margin: auto;
    width: 80%;

    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap:1em;

  }

  .responsive {
    width: 100%;
    height: auto;
  }

  @media screen and (min-width: 1200px){
    .center {
      padding: 80px;
    }
    }
</style>
