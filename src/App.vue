<script>
import TheHeader from "./components/TheHeader.vue"
import TheFooter from "./components/TheFooter.vue"

export default {
  components: {
    TheHeader,
    TheFooter
  }
}
</script>

<template>
  <TheHeader></TheHeader>

  <main>
    <h1>Content goes here</h1>
    <template>
      <ul class="nav flex-row">
        <li class="nav-item"><a href="#" class="nav-link"><img src="../assets/img/buy-comics-digital-comics.png" alt="">
            DIGITAL COMICS</a></li>
        <li class="nav-item"><a href="#" class="nav-link"><img src="../assets/img/buy-comics-merchandise.png" alt="">DC
            MERCHANDISE</a></li>
        <li class="nav-item"><a href="#" class="nav-link"><img src="../assets/img/buy-comics-subscriptions.png"
              alt="">SUBSCRIPTION</a></li>
        <li class="nav-item"><a href="#" class="nav-link"><img src="../assets/img/buy-comics-shop-locator.png"
              alt="">COMIC SHOP LOCATION</a></li>
        <li class="nav-item"><a href="#" class="nav-link"><img src="../assets/img/buy-dc-power-visa.svg" alt="">DC POWER
            VISA</a></li>
      </ul>
    </template>
  </main>

  <TheFooter> </TheFooter>
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

main {
  background-color: #1C1C1C;
  color: white;
}

main h1 {
  margin-bottom: 0;
  display: flex;
  justify-content: flex-start;
  padding: 3rem;
  font-size: 1.5rem;
}

template {
  background-color: #0082F9;
  display: flex;
  justify-content: space-between;
  align-content: center;
  align-items: center;
  font-size: .5rem;
}

template .nav-link {
  color: #ffffff;
  padding: 2rem;

}

template img {
  height: 2rem;
  margin: 1rem;
}

</style>
