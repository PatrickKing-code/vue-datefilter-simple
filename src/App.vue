<template>
  <div id="app">
    <date-filter></date-filter>
  </div>
</template>

<script>
import DateFilter from './components/DateFilter';
export default {
  name: "app",
  components: {
    DateFilter
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
