<template>
    <div id="HeaderBar">
        <h1>PostApp</h1>
        <ul>
            <li>Home</li>
            <li> <router-link to="/login">login</router-link></li>
            <li>signup</li>
        </ul>
    </div>
</template>

<script>
    export default {

    }
</script>

<style lang="scss" scoped>
    #HeaderBar{
        display: flex;
        justify-content: space-around;
        align-items: center;
        height:90px;
        width:1920px;
        background-color:#45AAF2;
    }

    h1{
        font-family: 'Lobster', cursive;
        color: white;
        font-size: 45px;
    }

    ul{
        list-style:none;
        font-family: 'Roboto', sans-serif;
        color: white;
    }

    li{
        padding: 35px;
        display: inline;
        font-size: 25px;
    }
</style>