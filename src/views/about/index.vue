<template>
  <n-space :vertical="true" :size="16">
    <project-introduction />
    <project-info />
    <pro-dependency />
    <dev-dependency />
  </n-space>
</template>

<script setup lang="ts">
import { NSpace } from 'naive-ui';
import { ProjectIntroduction, ProjectInfo, ProDependency, DevDependency } from './components';
</script>
<style scoped></style>
