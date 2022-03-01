<!--
 * @Author: your name
 * @Date: 2022-03-01 15:59:58
 * @LastEditTime: 2022-03-01 16:00:59
 * @LastEditors: your name
 * @Description: 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
 * @FilePath: /low-code-vue/src/pages/generate/template.vue
-->
<template>
  <div></div>
</template>

<script lang="ts">
import { defineComponent, reactive } from 'vue'
export default defineComponent({
  name: 'template-list',
  setup() {
    let list = reactive([])
    return {
      list
    }
  }
})
</script>

<style lang="less" scoped></style>
