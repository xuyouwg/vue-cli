<template>
    <div class="testb">
        <h2>test bbbb</h2>
        <ul>
            <li v-for="(v,i) in lists" :key="i">{{v}}</li>
        </ul>
    </div>
</template>

<script>
export default {
    name:'testB',    //别名
    data() {
        return {
            lists:[1,2,3,4,5]
        }
    }
}
</script>

<style>
.testb {
    background: #f60;
}
.testb ul li {

}
</style>