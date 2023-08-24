<script>
import TheHeader from "./components/TheHeader.vue";
import TheFooter from "./components/TheFooter.vue";
import charactersList from "./db/characters";

export default {
  components: {
    TheHeader,
    TheFooter
  },
  data() {
    return {
      charactersList
    };
  },
};
</script>

<template>
  <TheHeader></TheHeader>

  <main>

    <div class="jumbo-container">
      <img class="jumbotron" src="./assets/img/jumbotron.jpg" alt="">
    </div>

    <div class="gallery">
      <div class="gallery">
        <div class="row row-cols-6">
          <div class="col" v-for="(character, i) in charactersList" :key="`character_${i}`">
            <div class="card border-0 rounded-0 h-100 bg-transparent text-white">
              <img :src="character.thumb" alt="" />
              <div class="card-body p-0 pb-3 pt-3">
                {{ character.series }}
              </div>
            </div>
          </div>
        </div>
      </div>

    </div>

    <ul class="banner nav flex-row">
      <li class="nav-item"><a href="#" class="nav-link"><img src="./assets/img/buy-comics-digital-comics.png" alt="">
          DIGITAL COMICS</a></li>
      <li class="nav-item"><a href="#" class="nav-link"><img src="./assets/img/buy-comics-merchandise.png" alt="">DC
          MERCHANDISE</a></li>
      <li class="nav-item"><a href="#" class="nav-link"><img src="./assets/img/buy-comics-subscriptions.png"
            alt="">SUBSCRIPTION</a></li>
      <li class="nav-item"><a href="#" class="nav-link"><img src="./assets/img/buy-comics-shop-locator.png" alt="">COMIC
          SHOP LOCATION</a></li>
      <li class="nav-item"><a href="#" class="nav-link"><img src="./assets/img/buy-dc-power-visa.svg" alt="">DC POWER
          VISA</a></li>
    </ul>

  </main>

  <TheFooter> </TheFooter>
</template>

<style scoped>
.jumbo-container {
  height: 400px;
  overflow: hidden;
}

.jumbotron {
  height: 220%;
  width: 100%;
}

.banner.nav {
  padding-left: 6rem;
  padding-right: 6rem;

}

.gallery {
  background-color: #1C1C1C;
  color: white;
  padding: 2rem 5rem;
}
.gallery img {
  aspect-ratio: 1/1;
  width: 13rem;
}

.banner {
  background-color: #0082F9;
  display: flex;
  justify-content: space-between;
  align-content: center;
  align-items: center;
  font-size: .5rem;
}

.banner .nav-link {
  color: #ffffff;
  padding: 2rem;

}

.banner img {
  height: 2rem;
  margin: 1rem;
}
</style>
