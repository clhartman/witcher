<template>
  <div class="Reviews">
    <h1>The Kindest of Words:</h1>
    <div class="col-12 quote-section">
      <div class="card">
        <div class="card-body">
          <blockquote class="blockquote mb-0">
            <p>As close to home as I've ever gotten.</p>
            <footer class="blockquote-footer"><cite title="Source Title">Geralt of Rivia</cite>
            </footer>
          </blockquote>
        </div>
      </div>
      <div class="card">
        <div class="card-body">
          <blockquote class="blockquote mb-0">
            <p>Not the worst place I've stayed.</p>
            <footer class="blockquote-footer"><cite title="Source Title">Yennefer of Vengerberg</cite>
            </footer>
          </blockquote>
        </div>
      </div>
      <div class="card">
        <div class="card-body">
          <blockquote class="blockquote mb-0">
            <p>I mean, I hate it, but I'd die to protect it too, you know? Whatever, it's complicated. Two thumbs up.
            </p>
            <footer class="blockquote-footer"><cite title="Source Title">Lambert of Literally Anywhere but Here</cite>
            </footer>
          </blockquote>
        </div>
      </div>
      <div class="card">
        <div class="card-body">
          <blockquote class="blockquote mb-0">
            <p>I've fought for years to make this place what it is, and I'm proud of what I've accomplished.
            </p>
            <footer class="blockquote-footer"><cite title="Source Title">Vesemir of Kaer Morhen</cite>
            </footer>
          </blockquote>
        </div>
      </div>
    </div>
    <h2>Leave a Review!</h2>
    <form>
      <div class="form-group">
        <label for="userName"></label>
        <input type="text" class="form-control" id="userName" aria-describedby="" placeholder="What's your name">
      </div>
      <div class="form-group">
        <label for="location"></label>
        <input type="text" class="form-control" id="location" placeholder="Where are you from?">
      </div>
      <div class="form-group">
        <label for="comment"></label>
        <input type="text" class="form-control" id="comment" placeholder="How'd you like it?">
      </div>
      <button type="submit" class="btn btn-success">Submit</button>
    </form>
  </div>
</template>

<script>
  export default {
    name: "Reviews",
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
  .quote-section {
    height: 30vh;
    overflow-y: scroll;
  }
</style>
}