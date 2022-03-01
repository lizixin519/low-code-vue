<template>
  <a-layout class="generate-contaner">
    <a-layout-header>
      <a-space>
        <a-button>生成vue2代码</a-button>
        <a-button>生成vue3代码</a-button>
      </a-space>
    </a-layout-header>
    <a-layout class="main-area">
      <a-layout-sider class="template-container" width="300px">
        <template-list></template-list>
      </a-layout-sider>
      <a-layout-content class="main-container">Content</a-layout-content>
      <a-layout-sider class="props-container" width="300px">Sider</a-layout-sider>
    </a-layout>
  </a-layout>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import TemplateList from './template.vue'
export default defineComponent({
  name: 'generate-comp',
  components: {
    TemplateList
  }
})
</script>

<style lang="less" scoped>
.generate-contaner {
  display: flex;
  width: 100%;
  height: 100vh;
  .main-area {
    display: flex;
    .template-container {
      width: 300px;
      background: red;
    }
    .main-container {
      flex: 1;
      background: green;
    }
    .props-container {
      width: 300px;
      background: yellow;
    }
  }
}
</style>
