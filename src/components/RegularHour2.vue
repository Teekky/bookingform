<template>
  <div class="hours">
    <input type="radio" name="hour" />
    <label for="15h30">15H30</label>
  </div>
  <div class="hours">
    <input type="radio" name="hour" />
    <label for="16H00">16H00</label>
  </div>
  <br />
  <br />
  <br />
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
