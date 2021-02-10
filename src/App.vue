<template>
    <div id="app">
        <job-list />
    </div>
</template>

<script>
    import JobList from './components/JobList.vue'

    export default {
        name: 'App',
        components: {
            JobList
        }
    }
</script>
