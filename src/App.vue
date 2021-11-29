<template>
  <form>
    <div class="mg2-0">
      <SelectDate msg="" />
    </div>
    <div class="mg2-0">
      <p>Choose one of the available timeslots</p>
      <RegularHour msg="" />
      <PrimeHour msg="" />
      <RegularHour2 msg="" />
      <PremiumHour msg="" />
    </div>
    <div class="mg2-0">
      <Remove msg="" />
    </div>
    <div class="mg2-0">
      <Information msg="" />
    </div>
    <button class="w100" v-on:click="alert">Save and continue</button>
  </form>
</template>

<script>
import SelectDate from "./components/SelectDate.vue";
import RegularHour from "./components/RegularHour.vue";
import PrimeHour from "./components/PrimeHour.vue";
import RegularHour2 from "./components/RegularHour2.vue";
import PremiumHour from "./components/PremiumHour.vue";
import Remove from "./components/Remove.vue";
import Information from "./components/Information.vue";

/* J'ai réussi à créer une boucle avec le v-for sauf que du coup tout le reste du contenu bug
Je le mets quand même parce que j'ai vraiment perdu 1h pour trouver le bug...
import BoucleHour from "./components/BoucleHour.vue"; */

/* Désolé je n'ai pas réussi à faire l'alert on click sur le bouton mais j'ai essayé */

export default {
  name: "App",
  components: {
    SelectDate,
    RegularHour,
    PrimeHour,
    RegularHour2,
    PremiumHour,
    Remove,
    Information,
  },
  methods: {
    greet: function(event) {
      // `event` is the native DOM event
      alert(event.target.tagName);
    }
  }
};
</script>

<style>
body {
  background-color: rgb(243, 243, 243);
}

form {
  width: 1000px;
  margin: auto;
  padding: 2em 5em;
  background-color: white;
  box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 24px;
}

label {
  margin: 1em 0;
}

div {
  margin: 1em 0;
}

.hours {
  display: inline;
  border-radius: 10px;
  padding: 10px;
  margin: 1em 1em 1em 0;
}

/* CSS GENERAL */

.block {
  display: block;
}

.inline {
  display: inline;
}

.w100 {
  width: 100%;
}

.border {
  border-radius: 10px;
  border: 1px solid darkgrey;
  padding: 1em;
}

.mg2-0 {
  margin: 2em 0;
}

button {
  text-align: center;
  color: white;
  background-color: orange;
  padding: 1em;
  border: none;
}
</style>
