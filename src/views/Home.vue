<template>
  <div class="home">
    <div class="feature-card">
      <router-link to="/movie/tt0409591">
        <img
          src="https://www.gbposters.com/media/catalog/product/cache/2/image/9df78eab33525d08d6e5fb8d27136e95/a/b/abydco272_1.jpg"
          alt="Naruto Poster"
          class="featued-img"
        />
        <div class="detail">
          <h3>Naruto</h3>
          <p>
            Naruto Uzumaki, is a loud, hyperactive, adolescent ninja who
            constantly searches for approval and recognition, as well as to
            become Hokage, who is acknowledged as the leader and strongest of
            all ninja in the village.
          </p>
        </div>
      </router-link>
    </div>
  </div>
</template>









<script>
export default {};
</script>

<style lang="scss">
.home {
  .feature-card {
    position: relative;
    .featued-img {
      display: block;
      width: 100%;
      height: 300px;
      object-fit: cover;

      position: relative;
      z-index: 0;
    }

    .detail {
      position: absolute;
      left: 0;
      right: 0;
      bottom: 0;
      background-color: rgba(0, 0, 0, 0.6);
      padding: 16px;
      z-index: 1;

      h3 {
        color: #fff;
        margin-bottom: 16px;
      }
      p {
        color: white;
      }
    }
  }
}
</style>
