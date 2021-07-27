<template lang="">
    <div>
        <label><input type="radio" v-bind:value="radioValue1" v-model="picked">서울</label>
        <label><input type="radio" v-bind:value="radioValue2" v-model="picked">부산</label>
        <label><input type="radio" v-bind:value="radioValue3" v-model="picked">제주</label>
    </div>
    <span>체크한 지역:{{ picked }}</span>
</template>
<script>
export default {
    data() {
        return {
            picked:'',
            radioValue1:'서울',
            radioValue2:'부산',
            radioValue3:'제주',
        }
    }
}
</script>

<style lang="">
    
</style>