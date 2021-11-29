<template>
  <div id="regular">
      <input type="radio" name="hour" v-for="regular in regulars" :key="regular.hours"/>
      {{ regular.hours }}
  </div>
</template>

<script>
export default {
  el: '#regular',
  name: "RegularHour",
  props: {
    msg: String,
  },
  data() {
    return {
      regulars: [
        { hours : '12h00'},
        { hours : '12h30'},
        { hours : '13h00'},
      ]
    }
  }
};
</script>

<style>
</style>
