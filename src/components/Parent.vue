<template>
    <h3>Parent</h3>
    <Child :Title="Message" :Age="age" :Names="names" :UserInfo="userInfo"/>
</template>

<script>
import Child from './Child.vue'
export default {
    data() {
        return {
            Message: "动态 parent message",
            age: 20,
            names: ["a","b","c"],
            userInfo:{
                name:"abcd",
                age:1234
            }
        }
    }, 
    components: {
        Child
    }
}

</script>

