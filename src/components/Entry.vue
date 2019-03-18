<template>
<div>
    <h3>{{title}}</h3>
    <p>{{time_period}}</p>
    <p>{{role}}</p>
    <p>{{description}}</p>
</div>    
</template>

<script>
export default {
    props: {
        title: String,
        time_period: String,
        role: String,
        description: String
    }
}
</script>


<style scoped>

div {
    text-align:start
}

p {
    padding: 0px 60px
}


</style>
