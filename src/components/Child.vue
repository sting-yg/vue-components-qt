<template>
    <h3>Child</h3>
    <p>{{ title }}</p>
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
    props:["title"]

}

</script>

