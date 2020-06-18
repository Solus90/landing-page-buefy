<template>
  <div class="hero is-info is-fullheight is-bold">
    <div class="hero-body">
      <div class="container has-text-centered">
        <h1 class="title">{{ title }}</h1>
        <p class="is-size-5">{{ msg }}</p>
        <a href="#contactForm" class="button m-t-10">Contact Us</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Hero',
  props: {
    title: String,
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
    .m-t-10{
        margin-top: 10px;
    }
</style>