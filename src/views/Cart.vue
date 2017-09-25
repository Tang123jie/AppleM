<template>
<<<<<<< HEAD
	<div>
		<nav-header></nav-header>
		111
		<nav-footer></nav-footer>
	</div>
=======
     <div>
	 <nav-header></nav-header>
        <div class="center">
		<tr>
		<td v-for="(value,key,index) in memberDetail">{{ key }}</td>
		</tr>
		<tr>
		<td v-for="(value,key,index) in memberDetail">{{ value }}</td>
		</tr>
		</div>
	<nav-footer></nav-footer>	
     </div>
>>>>>>> 6687e184766f0aed8a7eeab6ceea12c89fb11ffc
</template>

<script>
    import './../assets/css/base.css'
	import './../assets/css/product.css'
	import NavHeader from '@/components/NavHeader.vue'
	import NavFooter from '@/components/NavFooter.vue'
	import NavBread from '@/components/NavBread.vue'
	import axios from 'axios'
	export default {
		created(){
			this.memberDetail = {
				name:'tangjie',
				age:20,
				address:"山东省潍坊市",
				tel:"18364615315"
			}

		},
		data() {
			return{
				   memberDetail : {} 
			}
		},
		components: {
			NavHeader,
			NavFooter,
			NavBread
		}
	}
</script>


<style>
<<<<<<< HEAD

=======
.center{
	width:800px;
	height:600px;
	border:solid black 1px;
	margin:20px  auto;
}
>>>>>>> 6687e184766f0aed8a7eeab6ceea12c89fb11ffc

</style>