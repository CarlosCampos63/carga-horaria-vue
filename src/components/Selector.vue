<template>
  <div class="navbar-item">
    <b-field>
      <b-radio-button v-model="radioButton" native-value="lectivas" type="is-primary">
        <span class="text">Horas lectivas</span>
        <b-icon icon="book-open"></b-icon>
      </b-radio-button>

      <b-radio-button v-model="radioButton" native-value="no-lectivas" type="is-primary">
        <span class="text">Horas no lectivas</span>
        <b-icon icon="book"></b-icon>
      </b-radio-button>
    </b-field>
  </div>
</template>

<script>
export default {
  name: "Selector",
  data() {
    return {
      radioButton: "lectivas"
    };
  }
};
</script>

<style>
.text {
  margin-right: 5px;
}
</style>

