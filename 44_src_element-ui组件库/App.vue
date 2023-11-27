<template>
    <div>
        <button>原生的按钮</button>
        <input type="text">
        <atguigu-row>
            <el-button>默认按钮</el-button>
            <el-button type="primary">主要按钮</el-button>
            <el-button type="success">成功按钮</el-button>
            <el-button type="info">信息按钮</el-button>
            <el-button type="warning">警告按钮</el-button>
            <el-button type="danger">危险按钮</el-button>
        </atguigu-row>
        <atguigu-date-picker
                placeholder="选择日期"
                type="date">
        </atguigu-date-picker>
        <atguigu-row>
            <el-button circle icon="el-icon-search"></el-button>
            <el-button circle icon="el-icon-s-check" type="primary"></el-button>
            <el-button circle icon="el-icon-check" type="success"></el-button>
            <el-button circle icon="el-icon-message" type="info"></el-button>
            <el-button circle icon="el-icon-star-off" type="warning"></el-button>
            <el-button circle icon="el-icon-delete" type="danger"></el-button>
        </atguigu-row>
    </div>
</template>

<script>
    export default {
        name: 'App',
    }
</script>
