<template>
    <div class="offset-md-3 offset-lg-4 offset-0 col-lg-4 col-md-6 mt-5">

      <div class="offset-1 offset-lg-2 col-lg-8 col-10 mb-4 mb-md-3">
        <img alt="Statping Login" class="embed-responsive" src="banner.png">
      </div>
      <div>
          <h1 id="title" class="col-12 text-center pt-4 mt-4 mb-3 header-title font-6">{{core.name}}</h1>
          <h5 id="description" class="col-12 text-center mb-5 header-desc font-3">{{core.description}}</h5>
      </div>
    </div>
</template>

<script>
export default {
  name: 'Header',
    computed: {
      core() {
          return this.$store.getters.core
      }
    }
}
</script>
