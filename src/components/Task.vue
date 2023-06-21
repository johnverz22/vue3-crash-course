<template>
    <h3>{{ task.text }}</h3>
</template>

<script>
export default{
    name: Task,
    props: {
        task: Object
    }
}
</script>