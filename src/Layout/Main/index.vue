<template>
    <router-view v-slot="{ Component }">
      <keep-alive>
        <component :is="Component" />
      </keep-alive>
    </router-view>
</template>

<script lang="ts" setup></script>


<style scoped lang="less">
/* 我的 scoped CSS */
</style>