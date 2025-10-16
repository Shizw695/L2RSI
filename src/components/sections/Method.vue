<script setup>
import method from '../mds/method.mdx';
</script>

<template>
  <div>
    <el-divider />

    <el-row justify="center">
        <el-col :xs="24" :sm="20" :md="16" :lg="12" :xl="12">
            <method />
            <img
              src="/public/img_framework_0516.jpg"
              alt="Introduction"
              style="width: 100%; display: block; margin: 0 auto 20px auto;"
            />
        </el-col>
    </el-row>

  </div>
</template>

<style scoped>
.el-col {
  text-align: justify;
}
</style>
