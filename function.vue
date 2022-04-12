<!DOCTYPE html>
<html>
<script src="https://cdn.jsdelivr.net/npm/vue@2.6.14/dist/vue.js"></script>
<body>

<h2>Vue.js</h2>

<div id="app">
  {{ message }}
</div>

<p>
<button onclick="myFunction()">Click Me!</button>
</p>

<script>
var myObject = new Vue({
  el: '#app',
  data: {message: 'Hello Vue!'}
})

function myFunction() {
    myObject.message = "Joe Max";
}
</script>

</body>
</html>
