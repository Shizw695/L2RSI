<script setup>
import Qualitative_Place_Recognition_Results from '../mds/Qualitative_Place_Recognition_Results.mdx';
</script>

<template>
  <div>
    <el-divider />

    <el-row justify="center">
        <el-col :xs="24" :sm="20" :md="16" :lg="12" :xl="12">
            <Qualitative_Place_Recognition_Results />
            <el-container class="video-container">
              <video controls muted preload playsinline>
                <source src="./L2RSI_video_100km2.mp4" type="video/mp4">
              </video>
            </el-container>
        </el-col>
    </el-row>

  </div>
</template>

<style scoped>
.video-container{
  margin: 20px 0px 0px 0px;
}

iframe, video {
  aspect-ratio: 16 / 9;
  width: 100%;
}
</style>
