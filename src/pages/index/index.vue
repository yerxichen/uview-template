<template>
    <view class="content">
        <image class="logo" src="/static/logo.png"></image>
        <view>
            <text class="title">{{title}}</text>
        </view>
        <u-button>默认按钮</u-button>
        <u-button type="primary">主要按钮</u-button>
        <u-button type="success">成功按钮</u-button>
        <u-button type="info">信息按钮</u-button>
        <u-button type="warning">警告按钮</u-button>
        <u-button type="error">危险按钮</u-button>
    </view>
</template>

<script>
    export default {
        data() {
            return {
                title: 'Hello'
            }
        },
        onLoad() {

        },
        methods: {}
    }
</script>

<style>
    .content {
        text-align: center;
        height: 400 upx;
    }

    .logo {
        height: 200 upx;
        width: 200 upx;
        margin-top: 200 upx;
    }

    .title {
        font-size: 36 upx;
        color: #8f8f94;
    }
</style>
