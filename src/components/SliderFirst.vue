<template>
  <div>
    <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="3000000"
      controls
      indicators
      background="#f1f1f3"
      style="color: black;"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >
      <b-carousel-slide>
        <template #img>
          <div class="slideImage">
            <h2>Sur Trëmma, créez une annonce en quelques clics pour donner une seconde vie à votre objet.</h2>
            <img
              src="../assets/emmaus-giving.5e0a47b5.svg"
              alt="image slot"
            >
          </div>
        </template>
      </b-carousel-slide>

       <b-carousel-slide>
        <template #img>
         <div class="slideImage">
            <h2>L’argent de la vente permettra au projet de votre choix de voir le jour !</h2>
            <img
              src="../assets/emmaus-check.e7bf2733.svg"
              alt="image slot"
            >
          </div>
        </template>
      </b-carousel-slide>

       <b-carousel-slide>
        <template #img>
          <div class="slideImage">
             <h2>Vous avez envie de faire du tri ? Profitez en pour soutenir un projet solidaire !</h2>
            <img
              src="../assets/emmaus-object.2d9db0ad.svg"
              alt="image slot"
            >
          </div>
        </template>
      </b-carousel-slide>

    </b-carousel>
  </div>
</template>

<script>
  export default {
    methods: {
      onSlideStart(slide) {
        this.sliding = true
      },
      onSlideEnd(slide) {
        this.sliding = false
      }
    }
  }
</script>

<style scoped>
.slideImage{
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  height: 90vh;
}
img{
  align-self:end;
  width: 50vw;
}

h2{
  color: black;
  padding:0 3em;
}
</style>