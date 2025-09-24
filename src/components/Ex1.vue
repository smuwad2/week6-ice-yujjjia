<script>
export default {
    // Add Code Here

    data() {

        return {
            message: 'Choose your favourite fruit: ',
            // fruit1: fruits[0],
            // fruit2: fruits[1],
            // fruit3: fruits[2]
            fruit1: "apple",
            fruit2: "orange",
            fruit3: "peach",

            // challenge: use array  
            fruits: ["apple", 'orange', 'peach']
        }
    }
}


</script>


<template>
    <div id="app">
        {{ message }} </br>
        {{ fruit1 }} <input type="radio" name="fruit">
        {{ fruit2 }} <input type="radio" name="fruit">
        {{ fruit3 }} <input type="radio" name="fruit">
    </div>

    <h3>Using Array</h3>
    {{ message }} </br>
    <span v-for="fruit in fruits">
        {{ fruit }} <input type="radio" name="fruit">
    </span>
</template>

<style scoped></style>
