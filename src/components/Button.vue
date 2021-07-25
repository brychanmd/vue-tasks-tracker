<template>
    <button :style="{ background: colour }" class="btn" @click="onClick()" >{{ text }}</button>
</template>

<script>
export default {
    name: 'Button',
    props: {
        text: {
            type: String
        },
        colour: {
            type: String
        }
    },
    methods: {
        onClick() {
            console.log('click')
        },
    }
}
</script>