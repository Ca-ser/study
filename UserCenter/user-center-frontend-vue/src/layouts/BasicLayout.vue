<template>
  <div id="basic-layout">
    <a-layout>
      <a-layout-header>Header</a-layout-header>
      <a-layout-content>Content</a-layout-content>
      <a-layout-footer class="footer">
        <a href="https://cn.bing.com/" target="_blank"> \\\必应一下/// </a>
      </a-layout-footer>
    </a-layout>
  </div>
</template>
<script setup lang="ts"></script>
<style scoped>
#basic-layout .footer {
  background-color: #b4c7c7;
  text-align: center;
  position: fixed;
  bottom: 0;
  left: 0;
  right: 0;
  padding: 16px;
}
</style>
