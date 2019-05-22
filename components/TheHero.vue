<template>
  <div class="hero-image">
    <div class="hero-text">
      <p1>THE QUICK, BROWN FOX JUMPS</p1>
      <h1>DJs flock by when MTV ax quiz prog. <br />Junk MTV quiz.</h1>
      <button
        style="background-color: #611AFF; font-size: 14px; border: none;color: white; height: 60px; width: 140px"
      >
        Explore now
      </button>
    </div>
  </div>
</template>
<style lang="scss" scoped>
/* The hero image */
.hero-image {
  /* Use "linear-gradient" to add a darken background effect to the image (photographer.jpg). This will make the text easier to read */

  background-image: url("~assets/RedHeadRedemption.png");

  /* Set a specific height */
  height: 700px;
  margin-top: -22px;
  /* Position and center the image to scale nicely on all screens */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}

/* Place text in the middle of the image */
.hero-text {
  text-align: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: white;
}
</style>
