<template>
    <h3>Child</h3>
    <p>{{ Title }}</p>
    <p>{{ Age }}</p>
    <ul>
        <li v-for="(item,index) of Names" :key="index">{{ item }}</li>
    </ul>
    <p>{{ UserInfo.name }}</p>
    <p>{{ UserInfo.age }}</p>
</template>

<script>

export default {

    data() {
        return {

        }
    },
    /**
     * props 传递数据 父级传到子级
     */
    props:["Title","Age","Names","UserInfo"]
    

}

</script>

