<template>
  <div>
    <label for="date" class="block">Select a day</label>
    <input
      type="date"
      name="date"
      value="2021-02-12"
      class="block w100 border"
    />
  </div>
</template>

<script>
export default {
  name: "SelectDate",
  props: {
    msg: String,
  },
};
</script>

<style>
</style>
