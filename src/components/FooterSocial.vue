<template>
  <div class="gen">
    <div class="container">
      <div class="flex">
        <div class="btn">
          <button>SIGN-UP NOW!</button>
        </div>

        <div class="social">
          <a href="#"><strong>FOLLOW US!</strong></a>
          <img src="../assets/img/footer-facebook.png" alt="" />
          <img src="../assets/img/footer-twitter.png" alt="" />
          <img src="../assets/img/footer-youtube.png" alt="" />
          <img src="../assets/img/footer-pinterest.png" alt="" />
          <img src="../assets/img/footer-periscope.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.gen {
  background-color: black;
  width: 100%;
}

.flex {
  display: flex;
  justify-content: space-between;
}

.social {
  display: flex;
  justify-content: space-around;
  align-items: center;
  width: 400px;
  padding: 20px;
}

img {
  width: 30px;
  height: 30px;
}

a{
    text-decoration: none;
    color: aqua;
}

.btn {
  display: flex;
  align-items: center;
  padding: 20px;
}

button {
  padding: 1rem;
  border: 3px solid blue;
  color: white;
  background-color: black;
}

.container{
    width: 90%;
    margin: auto;
}
</style>
