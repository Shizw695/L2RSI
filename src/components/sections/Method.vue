<script setup>
import method from '../mds/method.mdx';
</script>

<template>
  <div>
    <el-divider />

    <el-row justify="center">
        <el-col :xs="24" :sm="20" :md="16" :lg="12" :xl="12">
            <method />
        </el-col>
    </el-row>

  </div>
</template>

<style scoped>
.el-col {
  text-align: justify;
}
</style>
