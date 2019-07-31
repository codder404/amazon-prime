<template>
  <div id="app">
    <Header />
  </div>
</template>

<script>
import Header from './components/Header/Header';

export default {
  name: 'app',
  components: {
    Header
  }
}
</script>

<style>
  * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        outline: 0;
    }

    html, body, #root {
        height: 100%;
        width: 100%;
    }

    body {
        text-rendering: optimizeLegibility !important;
        -webkit-font-smoothing: antialised !important;
        background: #0F171E;
        font-family: Arial, Helvetica, sans-serif;
        color: #FFF;
    }
</style>
