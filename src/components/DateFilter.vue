<template>
  <div>
    {{ date }}
    <p>------------------------</p>
    {{ date | format("yyyy-MM-dd hh:mm:ss") }}
  </div>
</template>

<script>
export default {
  name: "dateFilter",
  data() {
    return {
      date: new Date()
    };
  }
};
</script>

<style></style>
