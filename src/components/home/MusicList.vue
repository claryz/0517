<template>
<div>
    duishvgnurhginr
    {{title}}<br>{{type}}
</div>
</template>
<script>
export default {
    created(){
        console.log(this.title)
        console.log(this.type)
    },
    props:{
        title:{
            type:String,
            default:'今日榜单'
        },
        type:{
            type:[String,Number],
        }
    }
}

</script>