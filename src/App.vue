<script setup lang="ts"></script>

<template>
  <div class="common-layout">
    <el-container>
      <el-header>Header</el-header>
      <el-main
        >Main
        <el-alert title="success alert" type="success" effect="dark" />
        <el-alert title="info alert" type="info" effect="dark" />
        <el-alert title="warning alert" type="warning" effect="dark" />
        <el-alert title="error alert" type="error" effect="dark" />
      </el-main>
      <el-footer>Footer</el-footer>
    </el-container>
  </div>
</template>

<style scoped lang="scss"></style>
