<template>
  <div class="hours">
    <input type="radio" name="hour" />
    <label for="12h00">12H00</label>
  </div>
  <div class="hours">
    <input type="radio" name="hour" />
    <label for="12H30">12H30</label>
  </div>
  <div class="hours">
    <input type="radio" name="hour" />
    <label for="13H00">13H00</label>
  </div>
  <div class="hours">
    <input type="radio" name="hour" />
    <label for="13H30">13H30</label>
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
  border: 2px solid lightgray;
}
</style>
