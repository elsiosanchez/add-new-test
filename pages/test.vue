<template>
  <el-card>
    <template #header>
      <div class="card-header">
        <span> {{ 'Test' }}</span>
        <NuxtLink to="/">
          <el-button type="primary" plain>
            Homepage
          </el-button>
        </NuxtLink>
      </div>
    </template>
    <el-tabs type="border-card" class="demo-tabs">
      <el-tab-pane>
        <template #label>
          <span class="custom-tabs-label">
            <el-icon><calendar /></el-icon>
            <span>Route</span>
          </span>
        </template>
        Route
      </el-tab-pane>
      <el-tab-pane label="Config">Config</el-tab-pane>
      <el-tab-pane label="Role">Role</el-tab-pane>
      <el-tab-pane label="Task">Task</el-tab-pane>
    </el-tabs>
  </el-card>
</template>

<script lang="ts" setup>
</script>
<style>
.demo-tabs > .el-tabs__content {
  padding: 32px;
  color: #6b778c;
  font-size: 32px;
  font-weight: 600;
}
.demo-tabs .custom-tabs-label .el-icon {
  vertical-align: middle;
}
.demo-tabs .custom-tabs-label span {
  vertical-align: middle;
  margin-left: 4px;
}
</style>
