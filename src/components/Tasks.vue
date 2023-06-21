<template>
    <div :key="task.id" v-for="task in tasks">
       <Task :task="tasks" />
    </div>
</template>

<script>
    import Task from './Task'
    
    export default {
        name: 'Tasks',
        props: {
            tasks: Array
        },
        components: {
            Task
        }
    }
</script>