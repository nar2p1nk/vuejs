<script>
export default {
   props:{count:Number}
}
</script>

<template>
    <div class='counter'>
        <h1>a counter</h1>
        <p>the count is {{count}}</p>
       <button @click='count++'>increase count</button>
   </div>
</template>
