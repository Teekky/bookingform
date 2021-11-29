<template>
  <div class="hours">
    <input type="radio" name="hour" />
    <label for="14h00">14H00</label>
  </div>
  <div class="hours">
    <input type="radio" name="hour" />
    <label for="14H30">14H30</label>
  </div>
  <div class="hours">
    <input type="radio" name="hour" />
    <label for="15H00">15H00</label>
  </div>
</template>

<script>
export default {
  name: "PrimemHour",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
.hours {
  border: 2px solid violet;
}
</style>
