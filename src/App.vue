<template >

   
    <div>
        <h1>hexoadmin 后台</h1>
        <el-input v-model='http' style="max-width: 600px" placeholder="Please input" ><template #prepend>请输入服务器源地址：</template></el-input>  <el-input v-model='http' style="max-width: 600px" placeholder="Please input" ><template #prepend>请输入APIkey：</template></el-input>
        <p>hello world</p>
    </div>
    
</template>
<script setup lang='ts'>
import {ref} from 'vue'
const http = ref('');
</script>
