<template>
  <div>
    <div class="parallax"></div>
    <div class="parallax-content">
      <p class="title">Company Profile</p>
    </div>

    <div class="container" style="margin-top:125px;">
      <nav aria-label="breadcrumb" role="navigation">
        <ol class="breadcrumb">
          <li class="breadcrumb-item"><a href="/">Home</a></li>
          <li class="breadcrumb-item active" aria-current="page">About Us</li>
        </ol>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: 'about',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.parallax {
    /* The image used */
    background-image: url("./../assets/blobid1494975991895.jpg");

    /* Set a specific height */
    min-height: 400px;

    /* Create the parallax scrolling effect */
    background-attachment: fixed;
    background-repeat: no-repeat;
    background-size:contain;
    background-position:  center;
}
.parallax-content{
  right: 0;
  padding:15px 15px 2px 15px;
  width:500px;
  background: rgb(255, 255, 255); /* Fall-back for browsers that don't support rgba */
  background: rgba(255,255,255, 0.8);
  margin-top: -200px;
  text-align: left;
}
.title{
  font-size: 32px;
}
</style>
