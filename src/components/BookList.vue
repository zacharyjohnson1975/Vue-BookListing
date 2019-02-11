<template>
    <div>
        <h1>{{title}}</h1>
    </div>
</template>

<script>
    export default {
        props: {
            name: {
                type: String,
                default: 'BookList'
            },
             title: {
                type: String,
                default: 'All Books' 
            },
        },
        methods: {
            data() {
                title = 'All Books'
                return title;
            }
        },
    }
</script>

<style scoped>
    h1,h2{
        font-weight:normal
    }
</style>