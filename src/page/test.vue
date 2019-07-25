<template>
    <div>
        <div>
            <div class="ani"></div>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {

        }
    }
}
</script>
<style scoped>
.ani {
    width: 10px;
    height: 100px;
    background-color: gray;
    -webkit-animation: aaa 20s
}
@-webkit-keyframes aaa {
    0% {bottom: 0px}
    100% {bottom: 200px}
}
</style>

