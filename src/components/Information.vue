<template>
  <div>
    <img
      src="https://cdn-icons.flaticon.com/png/512/2441/premium/2441296.png?token=exp=1638202229~hmac=507e66b8c23690caf186250ca34e7d69"
      alt=""/>
    <p class="inline m0-2">Info about available timeslots</p>
    <ul>
      <li>Regular slots <br>Free </li>
      <li class="green">Premium slots <br>INR 134 </li>
      <li class="violet">Prime slots <br>INR 254 </li>
    </ul>
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
.green {
  color: green;
}
.violet {
  color: violet;
}

img {
  width: 20px;
  margin-right: 1em;
}

div {
  background-color: lightblue;
  padding: 1em;
}

ul {
  display: flex;
  justify-content: space-around;
}
</style>
