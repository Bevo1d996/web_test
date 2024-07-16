<template>
  <div>
    <!-- 简易账户密码登录界面 -->
    <el-form
      :model="ruleForm2"
      label-position="left"
      label-width="0px"
      class="demo-ruleForm login-container"
    >
      <h3 class="title">系统登录</h3>
      <el-form-item prop="account">
        <el-input
          type="text"
          v-model="ruleForm2.account"
          auto-complete="off"
          placeholder="账号"
        ></el-input>
      </el-form-item>
    </el-form>
  </div>
</template>
<script setup>

</script>
<style></style>
