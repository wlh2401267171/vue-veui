<!--模板html结构-->
<template>
 <h1 class="demo">{{msg}}</h1>
</template>
<!--负责语法-->
<script >
	//export模块化的导出
	export default {
		data:function(){
			return{
				msg:'王炼辉1'
			};
			
		},methods:{},
		watch:{},
	}
	
</script>
<!--负责样式-->
<style lang="less">
.demo{
	color: red;
}
</style>
