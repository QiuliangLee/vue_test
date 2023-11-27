<template>
    <div>
        <Student :age="18" name="李四" sex="女"/>
    </div>
</template>

<script>
    import Student from './components/Student'

    export default {
        name: 'App',
        components: {Student}
    }
</script>
