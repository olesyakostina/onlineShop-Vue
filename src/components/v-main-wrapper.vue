<template>
    <div>
        <div class="v-main-wrapper">
            <keep-alive>
                <router-view></router-view>
            </keep-alive>
        </div>
    </div>
</template>

//
<script>
export default {
    name: "v-main-wrapper",
    components: {},
    props: {},
    data() {
        return {
            title: "Main wrapper",
        };
    },
    methods: {},
    watch: {},

    computed: {},
};
</script>

<style>
.v-main-wrapper {
    max-width: 900px;
    margin: 0 auto;
}
</style>
