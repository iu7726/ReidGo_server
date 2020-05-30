<style>
    .head-body-row{
        height: 60px;
    }

    .content{
        padding:0% 12%;
    }

    .content-banner{
        border:1px solid #000;
        height:450px;
        margin-bottom:3%;
    }

    .navi-item{
        padding: 3px;
        border-radius: 15px;
        background: #efefef;
        cursor: pointer;
    }
</style>

<template>
    <div class="content">
        <div class="head-body-row"></div>
        <div class="body-content">
            <div class="content-banner">
                banner
            </div>

            <div class="body-navi">
                <span class="navi-item" v-on:click="goCalender">
                    캘린더
                </span>
            </div>
        </div>
    </div>
</template>

<script>

    export default {

        mounted() {

            console.log('Component mounted.')

        },
        methods:{

            goCalender: function(){
                location.href = "/calendar";
            }

        }


    }

</script>
