<script>
export default {
    props:{
        isTrue:Boolean,
        message:String
    }
}
</script>

<template>
   <div class='boo'>
       <p>{{isTrue ? message: 'press the button if you dare...' }}</p>
       <button @click='isTrue = true' >Press me</button>
   </div>
</template>
