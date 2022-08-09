<template>
  <div class="home">
    <img src="./../assets/trade.png" alt="Trade" />
    <div class="items">
      <div class="card text-white bg-info mb-3" style="max-width: 99%">
        <div class="card-header">Categorias</div>
        <div class="card-body">
          <h5 class="card-title">Categories</h5>
          <p class="card-text">
            Os diversos tipos de produtos são divididos em categorias.
          </p>
        </div>
      </div>
      <div class="card bg-light mb-3" style="max-width: 99%">
        <div class="card-header">Header</div>
        <div class="card-body">
          <h5 class="card-title">Light card title</h5>
          <p class="card-text">
            Some quick example text to build on the card title and make up the
            bulk of the card's content.
          </p>
        </div>
      </div>
    </div>
  </div>

  <br />
</template>

<script>
// @ is an alias to /src

export default {
  name: "HomeView",
  components: {},
};
</script>
<style lang="scss" scoped>
.home {
  display: flex;
  justify-content: space-around;
  img {
    max-width: 40%;
    height: 320px;
  }
  .items {
    max-width: 50%;
  }
}
</style>