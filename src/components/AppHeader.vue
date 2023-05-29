<template>
  <header>
    <div class="conteiner d-flex">
      <div class="logo">
        <img
          src="src/assets/images/logo-restaurant-2x.png"
          alt=""
          style="height: 60px"
        />
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
  height: 700px;
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
  padding-top: 7rem;

  h3 {
    color: grey;
    font-size: 20px;
    padding-bottom: 1.5rem;
  }
  h1 {
    color: white;
    padding-bottom: 1.5rem;
  }
  p {
    color: grey;
    padding-bottom: 1.5rem;
  }
  button {
    background-color: black;
    color: white;
    font-size: 20px;
    border: 1px solid white;
  }
}
.nav_bar {
  width: 60%;
  background-image: url(../assets/images/slider52x.jpg);
  background-size: cover;
  background-repeat: no-repeat;
}
</style>
