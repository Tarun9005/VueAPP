<template>
<div>
<h2>The count is awesome :yes it is: {{count}}</h2>

<p>
<button @click="count+=1">Increment</button>
</p>
</div>
</template>

<script>
export default{
	data(){
	return {count:0};
	}
}
</script>