<template>
<div>
    <img :src="pic" :alt='name'>
    <h2>{{score}}</h2>
    <h3>{{title}}</h3>
</div>
</template>

<script>
export default {
    name:"Test",
    props:['title','score','pic','name']
    
}
</script>