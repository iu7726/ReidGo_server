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
            <ds-calendar-app :calendar="calendar"></ds-calendar-app>
        </div>
    </div>
</template>

<script>
    import { Calendar } from 'dayspan';

    export default {
        data: () => ({
            calendar: Calendar.months()
        }),
        mounted() {

            console.log('Component mounted.')

        },
        methods:{



        }


    }

</script>
