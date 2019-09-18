<template>
  <footer class="site-footer">
    <div>
      <p>Icons</p>
      <font-awesome-icon :icon="['fab', 'linkedin']" />
      <font-awesome-icon :icon="['fab', 'github']" />
      <font-awesome-icon :icon="['fab', 'facebook']" />
      <font-awesome-icon :icon="['fas', 'coffee']" />
    </div>
    {{ $siteConfig.siteName }} &copy; {{ new Date().getFullYear() }} - All
    Rights Reserved
    <br />
    Made with <span style="color: #e25555;">&#9829;</span> with Nuxt.js and
    Netlify
  </footer>
</template>

<script>
export default {
  name: 'SiteFooter'
}
</script>

<style scoped>
footer {
  background: #eee;
  padding: 20px 10px;
  text-align: center;
  transition: 0.5s ease all;
}
</style>
