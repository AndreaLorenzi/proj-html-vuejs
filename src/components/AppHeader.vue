<template>
  <header>
    <div class="conteiner d-flex">
      <div class="logo">
        <img src="../assets/images/avada-restaurant-logo-new-2x.png" alt="" />
        <div class="text">
          <h3>THE BEST TABLE IN TOWN</h3>
          <h1>FINE DINING EXPERIENCE</h1>
          <p>
            Pellentesque vitae viverra risus, sagittis. Venenatis ridiculus
            scelerisque nisi in urna nulla. Sit tempor a et nisl, ac felis.
          </p>
          <button class="black-button">EXPLORE THE MENU</button>
        </div>
      </div>
      <div class="nav_bar">
        <nav>
          <ul class="d-flex">
            <li v-for="item in menuItems" :key="item">{{ item.title }}</li>
            <li>
              <i class="fa-solid fa-cart-shopping" style="color: #ffffff"></i>
            </li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  data() {
    return {
      menuItems: [
        {
          title: "Home",
        },
        {
          title: "Culinary History",
        },
        {
          title: "Our Team",
        },
        {
          title: "Takeout",
        },
        {
          title: "bulletin",
        },
        {
          title: "Reservation",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
@import "../styles/_variables.scss";
.conteiner {
  background-color: $first-color;
  height: 500px;
  .logo {
    width: 40%;
  }
  ul {
    padding-top: 50px;
    align-items: center;
    gap: 30px;
    list-style: none;
    li {
      color: white;
    }
  }
}
.text {
  margin: auto;
  width: 60%;
  padding-top: 3rem;
  text-align: center;
  h3 {
    color: grey;
  }
  h1 {
    color: white;
  }
  p {
    color: grey;
  }
}
.nav_bar {
  width: 60%;
  background-image: url(../assets/images/slider52x.jpg);
  background-size: contain;
}
</style>
