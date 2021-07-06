<template>
    <div>
        <h1 style="margin-top:200px;text-align:center">Todo List</h1>
        <div class="todoListContainer">
            <addItem/>
            <list-view/>
        </div>
    </div>
</template>

<script>
import addItem from './addItem.vue'
import listView from './listView.vue'
    export default {
        components: {
            addItem,
            listView
        }
    }
</script>
<style scoped>
.todoListContainer {
    width: 400px;
    margin: auto;
    margin-top: 50px;
}
</style>
