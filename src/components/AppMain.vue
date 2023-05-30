<template>
  <main>
    <!-- sezione 1  -->
    <section>
      <div class="container_big">
        <!-- intro container -->
        <div class="container">
          <div class="text">
            <!-- testi box sinistro -->
            <p class="py-3">
              <strong>LOREM IPSUM, DOLOR SIT AMET </strong>consectetur
              adipisicing elit. Ab ex tempora rerum officiis illo laborum
              dignissimos excepturi! Quidem rerum consequuntur voluptatum est
              aspernatur vitae. Asperiores reprehenderit aliquam laboriosam
              explicabo incidunt.
            </p>
            <h2 class="py-2">
              FOOD IS OUR COMMON <br />GROUND, A UNIVERSAL <br />EXPERIENCE
            </h2>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. In
              similique sequi enim eligendi id quaerat. Quod doloremque magni
              temporibus, voluptatum, ipsum voluptatem consequuntur labore
              inventore repellat hic quisquam praesentium laboriosam!
            </p>
            <!-- firma -->
            <img src="../assets/images/signature.jpg" alt="" />
          </div>

          <!-- immagine box destro -->
          <div class="intro-image"></div>
        </div>
      </div>

      <!-- sushi menu -->
      <div class="conteiner d-flex">
        <div class="sushi">
          <img src="../assets/images/sushi-1.png" alt="" />
          <h3>THE BEST TABLE IN TOWN</h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi nobis
            natus nostrum quod maxime.
          </p>
          <button class="white-button">EXPLORE THE MENU</button>
        </div>

        <div class="sushi">
          <img src="../assets/images/sushi-2.png" alt="" />
          <h3>PERFECT FOR GROUPS</h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi nobis
            natus nostrum quod maxime.
          </p>
          <button class="white-button">MAKE A RESERVATION</button>
        </div>

        <div class="sushi">
          <img src="../assets/images/sushi-3.png" alt="" />
          <h3>FRESH PRODUCE EVERYDAY</h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi nobis
            natus nostrum quod maxime.
          </p>
          <button class="white-button">LEARN MORE ABOUT US</button>
        </div>
      </div>
    </section>
    <!-- sezione2 -->
    <section></section>
    <!-- sezione3 -->
    <section>
      <h3 class="title-section-3">What critics are saying about us</h3>

      <div class="reviews">
        <div class="big">
          <div class="left-box">
            <!-- <img src="../assets/images/blog72x.jpg" alt="" /> -->
          </div>
          <div class="box-sinistra">
            <div class="reviews-text">
              <h3>MEGGY STEWART</h3>
              <h2>NEW YORK TIMES</h2>
              <i class="fas fa-star"></i>
              <div class="line"></div>
              <p>
                Pellentesque vitae viverra risus, sagittis. Venenatis ridiculus
                scelerisque nisi in urna nulla. Sit tempor a et nisl, ac felis.
              </p>
              <p>Pellentesque vitae viverra risus, sagittis.</p>
              <button class="black-button">READ FULL ARTICLE</button>
            </div>
          </div>
        </div>
        <div class="big-sotto" style="padding-top: 2rem">
          <div class="reviews-text-sinistro" style="margin-right: 2rem">
            <h3>MARY MAXEY</h3>
            <h2>THE GUARDIAN</h2>
            <i class="fas fa-star"></i>
            <div class="line"></div>
            <p>
              Pellentesque vitae viverra risus, sagittis. Venenatis ridiculus
              scelerisque nisi in urna nulla. Sit tempor a et nisl, ac felis.
            </p>
            <button class="transp-button">READ FULL ARTICLE</button>
          </div>
          <div class="reviews-text-destro">
            <h3>PATRICK MONROE</h3>
            <h2>GLOBE AND MAIL</h2>
            <i class="fas fa-star"></i>
            <div class="line"></div>
            <p>
              Pellentesque vitae viverra risus, sagittis. Venenatis ridiculus
              scelerisque nisi in urna nulla. Sit tempor a et nisl, ac felis.
            </p>
            <button class="transp-button">READ FULL ARTICLE</button>
          </div>
        </div>
      </div>

      <div class="piatto">
        <p>KUNG PAO CHICKEN - $32</p>
      </div>
    </section>
    <!-- sezione 4 -->
    <section></section>
    <!-- sezione 5 -->
    <section></section>
    <!-- seziozne6 -->
    <section></section>
    <!-- sezione 7 -->
    <section></section>
    <!-- sezione 8 -->
    <section></section>
  </main>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@import "../styles/_variables.scss";

.container {
  margin: auto;
  width: 90%;
  display: flex;
}
.text {
  width: 50%;
  padding: 2rem;
}
.intro-image {
  margin: 2rem;
  width: 50%;
  background-image: url(../assets/images/info22x.jpg);
  background-size: cover;
}

.sushi {
  margin: auto;
  width: 23%;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 2rem;
}
// section 3
.title-section-3 {
  text-align: center;
  padding-bottom: 2rem;
  padding-top: 2rem;
}
.reviews {
  width: 100%;

  .big {
    display: flex;
    width: 75%;
    margin: auto;
    .left-box {
      display: flex;
      width: 50%;
      height: 550px;
      background-image: url(../assets/images/blog72x.jpg);
      background-size: cover;
    }
    .box-sinistra {
      background-color: $first-color;
      width: 50%;
    }
    .reviews-text {
      margin: auto;
      display: flex;
      flex-direction: column;
      width: 80%;
      background-color: $first-color;
      height: 550px;

      h3 {
        color: $third-color;
        font-size: 16px;
        padding-top: 30px;
      }
      h2 {
        color: $second-color;
        font-size: 50px;
        padding-top: 30px;
      }
      p {
        color: $third-color;
        padding-top: 30px;
      }
      button {
        width: 35%;
        background-color: $first-color;
        color: white;
        border: 1px solid white;
        padding: 1rem;
      }
    }
  }
  .big-sotto {
    display: flex;
    width: 75%;
    margin: auto;
    .reviews-text-sinistro {
      margin: auto;
      display: flex;
      flex-direction: column;
      width: 80%;
      background-color: $first-color;
      height: 500px;

      h3 {
        color: $third-color;
        font-size: 16px;
        padding-top: 30px;
      }
      h2 {
        color: $second-color;
        font-size: 50px;
        padding-top: 30px;
      }
      p {
        color: $third-color;
        padding-top: 30px;
      }
      button {
        width: 35%;
        background-color: $first-color;
        color: white;
        border: 1px solid white;
        padding: 1rem;
      }
    }
    .reviews-text-destro {
      margin: auto;
      display: flex;
      flex-direction: column;
      width: 80%;
      background-color: $first-color;
      height: 500px;

      h3 {
        color: $third-color;
        font-size: 16px;
        padding-top: 30px;
      }
      h2 {
        color: $second-color;
        font-size: 50px;
        padding-top: 30px;
      }
      p {
        color: $third-color;
        padding-top: 30px;
      }
      button {
        width: 35%;
        background-color: $first-color;
        color: white;
        border: 1px solid white;
        padding: 1rem;
      }
    }
  }
}
.piatto {
  width: 100%;
  margin-top: 2rem;
  background-image: url("../assets/images/page52x.jpg");
  background-size: cover;
  display: flex;
  height: 500px;
  justify-content: center;
  align-items: flex-end;
  color: white;
}
</style>
