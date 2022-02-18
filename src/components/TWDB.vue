<script>
export default {
    props:{data:String}
}
</script>


<template>
    <div class="TWDB">
        <h1>Two-way data binding</h1>
        <p>{{data}}</p>
        <input type="text" v-model="data">
    </div>
</template>
