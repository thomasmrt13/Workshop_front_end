<template>
    <div>
        <div id="LoginPage">
            <input type="text" placeholder="Username" v-model="username_input">
            <input type="password" placeholder="Password" v-model="password_input">
            <button @click="emitLogUser">Login</button>
        </div>
    </div>
</template>

<script>
    export default {

    }
</script>

<style lang="scss" scoped>
    #LoginPage{
        margin: 200px;
        padding: 200px;
        display: flex;
        width: 200px;
        height: 100px;
        background-color: #45AAF2;
        align-items: center;
    }
</style>