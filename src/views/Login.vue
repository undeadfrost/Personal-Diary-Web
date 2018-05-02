<template>
  <el-form>
    <el-form-item>
      <el-input type="number" v-model="mobile" suffix-icon="" placeholder="手机号"></el-input>
    </el-form-item>
    <el-form-item>
      <el-input type="password" v-model="password" suffix-icon="" placeholder="密码"></el-input>
    </el-form-item>
  </el-form>
</template>

<script>
import ElFormItem from "../../node_modules/element-ui/packages/form/src/form-item.vue";

export default {
  components: {ElFormItem},
  data () {},
  methods: {}
}
</script>
