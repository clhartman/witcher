<template>
  <div class="wintering-carousel">
    <div id="kaerMorhenCaptions" class="carousel slide" data-ride="carousel">
      <ol class="carousel-indicators">
        <li data-target="#kaerMorhenCaptions" data-slide-to="0" class="active"></li>
        <li data-target="#kaerMorhenCaptions" data-slide-to="1"></li>
        <li data-target="#kaerMorhenCaptions" data-slide-to="2"></li>
        <li data-target="#kaerMorhenCaptions" data-slide-to="3"></li>
        <li data-target="#kaerMorhenCaptions" data-slide-to="4"></li>
        <li data-target="#kaerMorhenCaptions" data-slide-to="5"></li>
        <li data-target="#kaerMorhenCaptions" data-slide-to="6"></li>
      </ol>
      <div class="carousel-inner item-size">
        <div class="carousel-item active item-size">
          <img src="../assets/exterior.png" class="d-block w-100" alt="Kaer Morhen Exterior">
          <div class="carousel-caption d-none d-md-block">
            <h5>Kaer Morhen</h5>
            <p>Nestled high in the beautiful mountain ranges of Kaedwen, this rustic retreat is sure to replenish your
              energy and remind you of the simpler pleasueres of life.</p>
          </div>
        </div>
        <div class="carousel-item item-size">
          <img src="../assets/tower-view.png" class="d-block w-100" alt="Tower View">
          <div class="carousel-caption d-none d-md-block">
            <h5>Scenic Overlooks</h5>
            <p>With sweeping views of the majestic mountain ranges, you will feel ready to conquer the world in no time.
            </p>
          </div>
        </div>
        <div class="carousel-item item-size">
          <img src="../assets/lake.jpg" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h5>The Lake at Kaer Morhen</h5>
            <p>This picturesque alpine lake is the perfect place to take a picnic lunch and practice some swordplay.</p>
          </div>
        </div>
        <div class="carousel-item item-size">
          <img src="../assets/stateroom.jpg" class="d-block w-100" alt="stateroom">
          <div class="carousel-caption d-none d-md-block">
            <h5>Your Luxury Stateroom</h5>
            <p>Any witcher who chooses to winter at Kaer Morhen will find a well-appointed room at his disposal, with
              plenty of amenities for himself and his invited guests.</p>
          </div>
        </div>
        <div class="carousel-item item-size">
          <img src="../assets/stateroom2.jpg" class="d-block w-100" alt="stateroom 2">
          <div class="carousel-caption d-none d-md-block">
            <h5>Your Luxury Stateroom</h5>
            <p>Our rooms are large and clasically furnished - providing you with ample room for any activities.</p>
          </div>
        </div>
        <div class="carousel-item item-size">
          <img src="../assets/dining-hall.jpg" class="d-block w-100" alt="dining hall">
          <div class="carousel-caption d-none d-md-block">
            <h5>The Dining Hall</h5>
            <p>Famished after a long day of sparring? Join us for a meal, served in the communal style, and enjoy
              pleasant conversation with other like-minded guests.</p>
          </div>
        </div>
        <div class="carousel-item item-size">
          <img src="../assets/conference.png" class="d-block w-100" alt="conference room">
          <div class="carousel-caption d-none d-md-block">
            <h5>The Conference Room</h5>
            <p>Need a space to plan a last-ditch standoff against an unrelenting spectral army? We have you covered!</p>
          </div>
        </div>
      </div>
      <a class="carousel-control-prev" href="#kaerMorhenCaptions" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="carousel-control-next" href="#kaerMorhenCaptions" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
  </div>
</template>

<script>
  export default {
    name: "WinteringCarousel",
    props: [],
    data() {
      return {}
    },
    computed: {},
    methods: {},
    components: {}
  }
</script>

<style scoped>
  .item-size {
    height: 90vh !important;
    width: 90vw !important;
    margin: auto;
  }

  .carousel-indicators>li {
    width: 10px !important;
    height: 10px !important;
    border-radius: 50%;
  }

  .wintering-carousel {
    padding-top: 10px;
  }
</style>