<template>
    <li ><a :href="obje.url">{{obje.title}}</a></li>
</template>

<script>
    //
    export default {
        name: "ItemNews",
        props: {
            obje: {
                type: Object,
                required: true
            }
        }
    }
</script>

<style scoped>

</style>