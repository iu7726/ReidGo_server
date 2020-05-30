<style>

    .head-body{
        height: 50px;
        position:fixed;
        background: #fff;
        width:75%;
        padding:0% 12%;
        z-index:10;
    }

    .head-logo{
        font-weight: bold;
        font-size: 2em;
        float: left;
    }

    .head-login{
        float:right;
        line-height: 54px;
    }

    .head-btn{
        background: #666666;
        padding: 3px 25px;
        font-weight: bold;
        cursor: pointer;
        border-radius: 15px;
    }

    .head-btn:hover{
        color:#fff;
    }

</style>

<template>
    <div class="head-body">
        <div class="head-logo">
            MHTOY
        </div>
        <div class="head-login">
            <span class="head-btn">Login</span>
            <span class="head-btn">Sign Up</span>
        </div>
    </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Component Header mounted.')
        }
    }
</script>