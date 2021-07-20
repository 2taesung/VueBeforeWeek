<template>
    <div>
        <label><input type="checkbox" true-value="가능" false-value="불가능" v-model="c">{{ c }}</label>
    </div>
</template>
<script>
export default {
    data() {
        return {
            c: "불가능"
        }
    }
    
}
</script>
<style lang="">
    
</style>