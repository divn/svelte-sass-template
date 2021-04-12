<script>
  import Header from './components/header.svelte'
  let first_name = 'Seppo'
</script>

<!-- Imported component header from src/components/header.svelte-->
<Header text={'This is a Header!'} />
<div class="main">
  <h1>svelte-sass-template</h1>
  <p class="red">SASS is working!</p>
  <p>Your name is {first_name}</p>
</div>

<!-- Remember type="text/scss" in style if u are using scss -->
<style type="text/scss">
  @import './sass/app.scss';
</style>
