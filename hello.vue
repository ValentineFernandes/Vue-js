<!DOCTYPE html>
<html>
<script src="https://cdn.jsdelivr.net/npm/vue@2.6.14/dist/vue.js"></script>
<body>

<div id="app">
  <h1>{{ message }}</h1>
</div>

<script>
var myObject = new Vue({
  el: '#app',
  data: {message: 'Hello Vue!'}
})
</script>

</body>
</html>
