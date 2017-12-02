<template>
  <div>
    <div class="parallax"></div>
    <div class="parallax-content">
      <p class="title">TD Customs Brokerage Services</p>
      <p>We are capable of catering to the requirements of any material that needs t be transported to any port around the world, including fast and reliable transportaion of urgent goods.</p>
    </div>

    <div class="container" style="margin-top:145px;">
      <nav aria-label="breadcrumb" role="navigation">
        <ol class="breadcrumb">
          <li class="breadcrumb-item active" aria-current="page">Home</li>
        </ol>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: 'index',
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
    background-image: url("./../assets/container_yard.jpg");

    /* Set a specific height */
    min-height: 500px;

    /* Create the parallax scrolling effect */
    background-attachment: fixed;
    background-repeat: no-repeat;
    background-size:auto;
    background-position: center bottom;
}
.parallax-content{
  padding:20px;
  width:500px;
  background: rgb(255, 255, 255); /* Fall-back for browsers that don't support rgba */
  background: rgba(255,255,255, 0.8);
  margin-top: -325px;
  text-align: left;
}
.title{
  font-size: 24px;
}
</style>
