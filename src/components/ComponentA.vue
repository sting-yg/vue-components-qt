<template>
    <h3>ComponentA</h3>
    <componentB :title="title" :age="age" :names="names"  />
</template>

<script>
import ComponentB from "./ComponentB.vue"
export default {
    data() {
        return {
            title:"标题",
            age:100,
            names:["a","b","c"]
        }
    },
    components: {
        ComponentB
    }
}
</script>