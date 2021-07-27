<template>
  <div>
    <tr :key="i" v-for="(pruduct, i) in productList">
      <td>{{ product.product_name }}</td>

    </tr>
  </div>
</template>
<script>
import ApiMixin from ''
export default {
  data() {
    return {
      productLis: []
    }
  },
  created() {
    this.getList();
  },
  methods: {
    async getList() {
      this.productList = await this.$api("API", "get");
    }
  }
}
</script>
<style lang="">
  
</style>