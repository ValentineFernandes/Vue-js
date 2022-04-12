<!DOCTYPE html>
<html>
<script src="https://cdn.jsdelivr.net/npm/vue@2.6.14/dist/vue.js"></script>
<body>

<h2>Vue.js</h2>

<div id="app">
  <p>{{ message }}</p>
  <p><input v-model="message"></p>
</div>

<script>
myObject = new Vue({
  el: '#app',
  data: {message: 'Hello Vue.js!'}
})
</script>

</body>
</html>
