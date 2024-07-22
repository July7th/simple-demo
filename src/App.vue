<template>
  <n-button @click="showModal = true">
    来吧
  </n-button>
  <n-modal v-model:show="showModal" style="width: 60vw" preset="card" >
    <NImage width="100" src="https://07akioni.oss-cn-beijing.aliyuncs.com/07akioni.jpeg"/>
  </n-modal>
</template>

<script setup>
import { ref } from "vue";
import { NButton,NModal,NImage } from 'naive-ui'

const showModal = ref(false);
</script>
