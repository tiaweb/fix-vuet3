<template>
  <footer class="footer">
    <div class="container-fluid">
      <ul class="nav">
        <li class="nav-item">
          <a class="nav-link" href="https://tiaweb.github.io/">
            Tiaweb
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="">
            Blog
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="">
            Suport
          </a>
        </li>
      </ul>
      <div class="copyright">
        © {{year}}  
        <a href="https://tiaweb.github.io" target="_blank" rel="noopener">Tiaweb</a> for a better web.
      </div>
    </div>
  </footer>
</template>
<script>
  export default {
    data() {
      return {
        year: new Date().getFullYear()
      }
    }
  };
</script>
<style>
</style>
