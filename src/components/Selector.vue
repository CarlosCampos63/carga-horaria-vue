<template>
    <section>
    <b-field>
        <b-radio-button v-model="radioButton"
            native-value="Nope"
            type="is-primary">
            <b-icon icon="check"></b-icon>
            <span>Horas lectivas</span>
        </b-radio-button>

        <b-radio-button v-model="radioButton"
            native-value="Yep"
            type="is-primary">
            <b-icon icon="check"></b-icon>
            <span>Horas no lectivas</span>
        </b-radio-button>
    </b-field>

</section>
</template>

<script>
export default {
    name: 'Selector',
    data() {
        return {
            radioButton: ''
        }
    }
}
</script>

<style>

</style>
