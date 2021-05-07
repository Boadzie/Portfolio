<template>
  <div>
    <nuxt/>
    <footer class="container footer">
      <div class="container">
        <div class="content has-text-centered has-text-white">
          <p>
            <p>copyright &copy; {{date.getFullYear()}} Daniel  Boadzie </p>
          </p>
        </div>
      </div>
    </footer>
  </div>
</template>


,<script>
export default {
  data() {
    return {
       date: new Date()
    }   
  },

}
</script>

<style>
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  background:  #ebedef;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.footer{
  margin-top: 50px;
  padding-bottom: 10px;
  background: #17202a;
  border-radius: 5px;
}
</style>
