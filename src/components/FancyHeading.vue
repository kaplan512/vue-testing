<template>
    <div>
        <span :style="headingStyles">{{title}}</span>
        <span>test</span>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                headingStyles: {
                    color: this.color
                }
            };
        },
        props: ["title", "color"]
    };
</script>

<style scoped>

</style>
