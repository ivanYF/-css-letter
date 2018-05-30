<template>
    <div id="app">
        <div class="font" data-id="A">
            <div class="a"></div>
        </div>
        <div class="font" data-id="B">
            <div class="b"></div>
        </div>
        <div class="font" data-id="C">
            <div class="c"></div>
        </div>
        <div class="font" data-id="D">
            <div class="d"></div>
        </div>
        <div class="font" data-id="E">
            <div class="e"></div>
        </div>
        <div class="font" data-id=""><div class=""></div></div>
        <div class="font" data-id=""><div class=""></div></div>
        <div class="font" data-id=""><div class=""></div></div>
        <div class="font" data-id=""><div class=""></div></div>
        <div class="font" data-id=""><div class=""></div></div>

    </div>
</template>

<script>
export default {
    name: 'App',
    components: {}
}
</script>

<style scoped lang="scss">
#app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    width: 100%;
    text-align: center;
    .font{
        width: 200px;
        height: 200px;
        display: inline-block;
        margin: 20px;
        overflow: hidden;
        border: 1px solid #999;
        .e{
            width: 60px;
            height: 100px;
            border-width: 15px 0 15px 15px;
            border-style: solid;
            border-color: #000;
            position: relative;
            left: 55px;
            top: 30px;
            &:after{
                content: '';
                width: 60px;
                height: 15px;
                background-color: #000;
                position: absolute;
                top:40px;
                left: 0;
            }
        }
        .d{
            position: relative;
            top:50px;
            left: 60px;
            width: 0;
            height: 95px;
            border-left: 15px solid #000;
            &:after{
                content: '';
                position: absolute;
                width: 50px;
                height: 65px;
                border-width: 15px 10px 15px 0;
                border-color: #000;
                border-style: solid;
                border-top-right-radius: 50%;
                border-bottom-right-radius: 50%;
            }
        }
        .c{
            width: 80px;
            height: 90px;
            border: 15px solid #000;
            border-radius: 50%;
            position: relative;
            left: 50px;
            top: 40px;
            &:after{
                content: '';
                width: 65px;
                height: 65px;
                background: #fff;
                position: absolute;
                right: -30px;
                top:12px;
                transform:rotate(45deg);
            }
        }
        .b{
            position: relative;
            top:30px;
            left: 50px;
            width: 0;
            height: 140px;
            border-left: 15px solid #000;
            &:after{
                content: '';
                position: absolute;
                width: 50px;
                height: 45px;
                border-width: 15px 10px 15px 0;
                border-color: #000;
                border-style: solid;
                border-top-right-radius: 50%;
                border-bottom-right-radius: 50%;
            }
            &:before{
                content: '';
                position: absolute;
                bottom: 0;
                width: 50px;
                height: 45px;
                border-width: 15px 10px 15px 0;
                border-color: #000;
                border-style: solid;
                border-top-right-radius: 50%;
                border-bottom-right-radius: 50%;
            }
        }
        .a{
            width: 60px;
            height: 100px;
            border-bottom: 15px solid #000;
            position: relative;
            left: 70px;
            top: -10px;
            &:after{
                content: '';
                width: 15px;
                height: 130px;
                position: absolute;
                left: -4px;
                top:40px;
                background-color: #000;
                transform:skew(-22deg);
            }
            &:before{
                content: '';
                width: 15px;
                height: 130px;
                position: absolute;
                right: -4px;
                top:40px;
                background-color: #000;
                transform:skew(22deg);
            }
        }
    }
}
</style>
