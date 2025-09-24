<script>
export default {
    data() {
        return {
            width: '200',
            height: '200',
            myImg: '/assets/me.png'
        }
    },
}
</script>

<template>

    <!-- add code here -->
    <img v-bind:src="myImg" v-bind:width="width" :height="height"></img>
    <!-- can just type colon without typing v-bind so many times -->
     <!-- i.e. : is a short-hand notation for v-bind -->


</template>
