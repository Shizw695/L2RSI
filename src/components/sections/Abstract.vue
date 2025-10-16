<script setup>
import abstract from '../mds/abstract.mdx';
</script>

<template>
  <div>
    <el-divider />

    <el-row justify="center">
        <el-col :xs="24" :sm="20" :md="16" :lg="12" :xl="12">
            <img
              src="/public/introduction4.jpg"
              alt="Introduction"
              style="width: 100%; display: block; margin: 0 auto 20px auto;"
            />

            <abstract />
        </el-col>
    </el-row>

  </div>
</template>

<style scoped>
.el-col {
  text-align: justify;
}
</style>
