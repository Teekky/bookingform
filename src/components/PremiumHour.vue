<template>
<div class="hours">
    <input type="radio" name="hour" />
    <label for="18h00">18H00</label>
  </div>
  <div class="hours">
    <input type="radio" name="hour" />
    <label for="18H30">18H30</label>
  </div>
  <div class="hours">
    <input type="radio" name="hour" />
    <label for="19h00">19H00</label>
  </div>
  <div class="hours">
    <input type="radio" name="hour" />
    <label for="19H30">19H30</label>
  </div>
</template>

<script>
export default {
  name: "RegularHour",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
.hours {
  border: 2px solid green;
  margin-top: 2em;
}
</style>
