<template>
  <div style="margin-top: 15px;width:50%;margin-left: 15px;">
    <el-input v-model="input3" placeholder="请输入内容" class="input-with-select">
      <el-select slot="prepend" v-model="select" placeholder="请选择">
        <el-option label="学号" value="1" />
        <el-option label="姓名" value="2" />
      </el-select>
      <el-button slot="append" icon="el-icon-search" />
    </el-input>
  </div>
</template>

<style>
  .el-select .el-input {
    width: 130px;
  }
  .input-with-select .el-input-group__prepend {
    background-color: #fff;
  }
</style>
<script type="text/javascript">
export default {
  data() {
    return {
      input1: '',
      input2: '',
      input3: '',
      select: ''
    }
  }
}
</script>
