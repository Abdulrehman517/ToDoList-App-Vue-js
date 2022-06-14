<template>

<div>
    <button v-on:click="updateTitle"> update title</button>

</div>
</template>

<script>
export default {
    name: 'Child-vue',
    methods: {
        updateTitle() {
            this.$emit('changeTitle', 'Props has been Updated!!!')
        }
    }


}
</script>