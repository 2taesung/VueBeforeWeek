<template lang="">
    <div class="container" :class="{
        'activate': isActive, 'text-red': hasError
    }">Class Binding</div>
</template>
<script>
export default {
    data() {
        return {
            isActive: false,
            hasError: true
        }
    }
}
</script>
<style scoped>
    .container {
        width: 100%;
        height: 200px;
        border-color: black;
        border: 5px solid;
    }
    .activate {
        background-color: yellow;
        font-weight: bold;
    }
    .text-red {
        color: red;
    }
    
</style>