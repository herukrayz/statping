<template>
    <div>
        <div class="offset-md-3 offset-lg-4 offset-0 col-lg-4 col-md-6 mt-5">
          <img alt="Statping Login" class="embed-responsive" src="banner.png">
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
