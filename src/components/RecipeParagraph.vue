<template>
    <p>{{ paragraph }}</p>
</template>

<script>
export default {
    props: {
        paragraph: {
            type: String,
            required: true,
        }
    }
}
</script>

<style>

</style>