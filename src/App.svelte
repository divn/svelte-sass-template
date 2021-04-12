<script>
</script>

<div class="main">
  <h1>svelte-sass-template</h1>
  <p>SASS is working!</p>
</div>

<style type="text/scss">
  @import './sass/global.scss';
  $color: red;
  .main {
    p {
      background: $color;
    }
  }
</style>
