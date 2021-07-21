<template lang="">
    <div>
        <input type="text" v-model="textValue">
        <button type="button" :disabled="textValue==''">Click</button>
    </div>
</template>
<script>
export default {
    data() {
        return {
            textValue:""
        }
    }
}
</script>
<style lang="">
    
</style>