<template>
    <div class="page-home">
        <ui-header></ui-header>
        <main class="page-body">
            <div class="container">
                这是首页内容
                <router-link to="/about">关于</router-link>
                <img src="/static/img/page.jpg" style="width: 100%">
            </div>
        </main>
        <ui-footer>

        </ui-footer>
    </div>
</template>

<script>
    export default {
        data () {
            return {
            }
        }
    }
</script>

<style scoped>
</style>
