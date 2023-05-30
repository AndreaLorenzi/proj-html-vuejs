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
    <section></section>
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
</style>
