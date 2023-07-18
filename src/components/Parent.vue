<template>
    <h3>Parent</h3>
    <Child :title="message"/>
</template>

<script>
import Child from './Child.vue'
export default {
    data() {
        return {
            message: "动态 parent message"
        }
    }, 
    components: {
        Child
    }
}

</script>

