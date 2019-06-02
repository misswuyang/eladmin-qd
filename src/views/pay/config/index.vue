<template>
  <div class="app-container">
    <el-row :gutter="20">
      <el-col :xs="24" :sm="24" :md="8" :lg="6" :xl="5">
        <el-card class="box-card">
          <div slot="header" class="clearfix">
            <span>支付宝</span>
          </div>
          <div>
            <div style="text-align: center">
              <el-upload
                action="https://jsonplaceholder.typicode.com/posts/"
                list-type="picture-card">
                <i class="el-icon-plus" />
              </el-upload>
              <el-dialog :visible.sync="dialogVisible">
                <img :src="dialogImageUrl" width="100%" alt="">
              </el-dialog>
            </div>
          </div>
        </el-card>
      </el-col>
      <el-col :xs="24" :sm="24" :md="8" :lg="6" :xl="5">
        <el-card class="box-card">
          <div slot="header" class="clearfix">
            <span>微信</span>
          </div>
          <div>
            <div style="text-align: center">11</div>
          </div>
        </el-card>
      </el-col>
      <el-col :xs="24" :sm="24" :md="8" :lg="6" :xl="5">
        <el-card class="box-card">
          <div slot="header" class="clearfix">
            <span>QQ</span>
          </div>
          <div>
            <div style="text-align: center">11</div>
          </div>
        </el-card>
      </el-col>
      <el-col :xs="24" :sm="24" :md="8" :lg="6" :xl="5">
        <el-card class="box-card">
          <div slot="header" class="clearfix">
            <span>银联</span>
          </div>
          <div>
            <div style="text-align: center">11</div>
          </div>
        </el-card>
      </el-col>
    </el-row>
  </div>
</template>
<style scoped>

</style>
