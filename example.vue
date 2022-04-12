<template>
  <header>
    <h1>Vue js Example</h1>
  </header>
  
  <section class="page-home">
    <a href="#/Page-1">Page-1</a>
    <a href="#/Page-2">Page-2</a>
  </section>
</template>

<script>
export default {
  name: "HomePage"
};
</script>

<style>
  /** creating some base styles */
  :root {
    --bkColour:  #fefefe;
    --fontColour: #222;
    --highlightColour: tomato;
    --spacing: 2rem;
  }
  html, body {
    margin: 0px; padding: 0px;
  }
  body {
    background-color: var(--bkColour);
    font-family: Avenir, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color:  var(--fontColour);
    font-size: 100%;
  }
  h1, h2, h3 {
    margin-bottom: var(--spacing);
  }
  p {
    font-size: calc(var(--spacing)/0.6);
  }
  label, input, button, select {
    padding: 4px 8px;
    font-family: Avenir, sans-serif;
    font-size: 100%;
  }
  code {
    font-size: 120%;
  }
  button {
    background-color: var(--bkColour);
    border: 4px solid var(--highlightColour);
    color: var(--highlightColour);
    font-weight: bold;
  }
  button:hover {
    background-color: var(--highlightColour);
    color:  var(--bkColour);
    cursor: pointer;
  }
  a {
    color: var(--highlightColour);
    text-decoration: underline;
  }
  a:hover {
    text-decoration: none;
  }
  .app-container {
    margin: var(--spacing);
  }
</style>

<style scoped>
  .page-home {}
  .page-home a {
    display:  block;
    padding:  var(--spacing);
    margin: var(--spacing);
    border:  2px solid var(--fontColour);
    border-radius: 20px;
    box-shadow:
      inset 2em 0.5em #ddd,
      0.3em 0.3em var(--highlightColour)
    ;
    text-align: center;
    text-decoration: none;
    font-size: 4rem;
  }
  .page-home a:hover {
    transform: translate(10px, 10px);
    box-shadow:
      inset 2em 0.5em #ddd,
      0.2em 0.2em var(--highlightColour)
    ;
  }
</style>


