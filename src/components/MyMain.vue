<template>
  <main>
    <section class="sectionup">
      <div class="container-cards">
        <MyCards />
      </div>
    </section>
    <section class="sectiondown">
      <div>
        <ul>
          <li>
            <img src="img/buy-comics-digital-comics.png" alt="" srcset="" />
            <span>Digital comics</span>
          </li>
          <li>
            <img src="img/buy-comics-merchandise.png" alt="" srcset="" />
            <span>Dc merchandise</span>
          </li>
          <li>
            <img src="img/buy-comics-subscriptions.png" alt="" srcset="" />
            <span>subscriptions</span>
          </li>
          <li>
            <img src="img/buy-comics-shop-locator.png" alt="" srcset="" />
            <span>shop-locator</span>
          </li>
          <li>
            <img src="img/buy-comics-digital-comics.png" alt="" srcset="" />
            <span>Digital comics</span>
          </li>
        </ul>
      </div>
    </section>
  </main>
</template>

<script>
import MyCards from "@/components/MyCards.vue";

export default {
  name: "MyMain",
  components: {
    MyCards,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.sectionup {
  background-color: #1c1c1c;
  margin-bottom: 0;
  div {
    width: 90%;
    height: auto;
    margin: auto;
    display: flex;
    align-items: center;
  }
}
h2 {
  color: white;
}
.sectiondown {
  background-color: #0282f9;
  padding-top: 10px;
  div {
    width: 90%;
    height: 100px;
    margin: 0 auto;
  }
}
ul {
  display: flex;
  justify-content: space-around;
}
li {
  display: flex;
  text-decoration: none;
  align-items: center;
  margin: auto 7px;
}
.container-cards {
    height: auto;
}
img {
    width: 60px ;
    height: 80px;
}
span {
  color: white;
}
</style>
