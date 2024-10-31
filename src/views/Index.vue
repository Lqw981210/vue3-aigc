<template>
    <div class="common-layout">
        <el-container>
            <el-header>AIGC</el-header>
            <el-main>
                <div class="topArea"></div>
                <div class="sendArea"></div>
            </el-main>
        </el-container>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    setup() {


        return {}
    }
})
</script>

<style lang="scss" scoped>
.common-layout {
    width: 100%;
    height: 100%;

    .el-container {
        width: 100%;
        height: 100%;

        .el-header {
            display: flex;
            align-items: center;
            justify-content: center;
            height: 10%;
            width: 100%;
            text-align: center;
            background-color: rgb(148, 105, 105);
            color: #FFF;
            font-size: calc(2vw);
        }

        .el-main {
            height: 90%;
            .topArea {
                height: auto;
            }
            .sendArea{
            height: 10%;
            background-color: red;
            }
        }
    }
}
</style>