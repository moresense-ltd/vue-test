<template>
    <div>
        <div v-for="todo in todos" v-bind:key="todo.id">
            {{todo.id}}


        </div>
    </div>
</template>

<script>
    export default {
        name: 'TodoList',
        data() {
            return {
                "todos": [
                    {
                        id: "1",
                        title: "Test 2"
                    },
                    {
                        id: "2",
                        title: "Test 2"
                    }
                ]
            }
        }
    }
</script>

<style scoped>

</style>
