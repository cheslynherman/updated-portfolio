<template>
  <section id="homepage">
    <div class="home">
      <div class="land-name my-auto">
        <h1 class="name">Cheslyn Herman</h1>
        <div class="words">
          <div>
            <h3 class="land-words">Innovative</h3>
          </div>
          <div>
            <h3 class="land-words">Confident</h3>
          </div>
          <div>
            <h3 class="land-words">Determined</h3>
          </div>
        </div>
      </div>
      <div class="land-image">
        <img
          src="https://i.postimg.cc/05cYv7dG/Blue-Beige-Minimalist-Smear-Elegant-Initials-Monogram-Logo-5-removebg-preview.png"
          class="logoImg"
        />
      </div>
    </div>
  </section>
</template>

<script>
export default {
  components: {},
};
</script>

<style scoped>
#homepage {
  background-color: #1b1717;
  color: #f6f2d4;
  height: 75vh;
}
.logoImg {
  height: 450px;
}
.land-name {
  align-items: center;
  margin-left: 50px;
  font-family: "Bebas Neue", sans-serif;
}
.home {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 20px;
}
.land-name,
.land-image {
  width: 50%;
}
.name {
  font-size: 90px;
}

.land-words {
  font-size: 50px;
}
.words {
  display: flex;
  justify-content: space-between;
  margin: 20px;
}
</style>
