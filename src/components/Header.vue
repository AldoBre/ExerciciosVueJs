<template>
    <ol>
        <li><a href="#">home</a></li>
        <li><a href="#">home</a></li>
        <li><a href="#">home</a></li>
        <li><a href="#">home</a></li>
       
    </ol>

</template>

<script>
export default{
    name: 'Header'
}
</script>

 <style scoped>
    ol{
        list-style: none;
        display:flex;
    }
    li{
        margin-right: 10px;
    }
    a{
        color: #DDD;
        text-decoration: none;
        transition: 0.5s;
    }

    a:hover{
        color:turquoise
    }
</style>