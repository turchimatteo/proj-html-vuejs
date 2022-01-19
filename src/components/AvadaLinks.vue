<template>
    <ul>
        <li v-for="(link, index) in links" :key="index" :class="{current: link.current}">
            <a href="link.url"> > {{ link.text }}</a>
        </li>
    </ul>
</template>
<script>
export default {
    name: "AvadaLinks",
    props: ['links'],
    data: function() {
        return {

        };
    }
}
</script>
<style lang="scss" scoped>
ul {
    list-style-type: none;
    li {
        margin-top: 15px;
    }
    a {
        list-style-type: none;
        color: black;
        text-decoration: none;
        margin-top: 20px;
    }
}
</style>