<template>
<div>
  <p>Can't find the time you are looking for ?</p>
  <img src="https://cdn-icons-png.flaticon.com/512/845/845646.png" alt="">
  <p class="inline m0-2">You have been added to the waiting list</p>
  <span>Remove</span>
</div>
</template>

<script>
export default {
  name: "Remove",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
img {
  width: 20px;
}
span {
  color: red;
}

.m0-2 {
  margin: 0 1em;
}

div {
  background-color: lightpink;
  padding: 1em;
}
</style>
