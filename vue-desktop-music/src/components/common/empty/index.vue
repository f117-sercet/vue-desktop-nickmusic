<template>
    <div class="empty flex-column">
        <img src="../../../assets/images/empty.png" alt="">
        <p>{{ emptyText }}</p>
    </div>
</template>

<script>
    export default {
        data() {
            return {

            };
        },
        props: {
            emptyText: {
                type: String,
                default: '别找了，没了'
            }
        },
        components: {},
        computed: {},
        watch: {},
        methods: {

        },
        created() {

        },
        mounted() {

        },
    }
</script>
<style lang='stylus' scoped>
    .empty {
        width: 100%;
        img {
            width: 300px;
        }
    }
</style>
