<template>
  <div class="wintering">
    <div class="row">
      <div class="col">
        <wintering-carousel />
      </div>
    </div>
    <div class="row d-flex justify-content-center">
      <reviews />
    </div>

  </div>
</template>

<script>
  import WinteringCarousel from "@/components/WinteringCarousel.vue"
  import Reviews from "@/components/Reviews.vue"

  export default {
    name: "wintering",
    props: [],
    data() {
      return {}
    },
    computed: {},
    methods: {},
    components: {
      WinteringCarousel,
      Reviews
    }
  }
</script>