<script>

import count from './components/count.vue';
import boo from './components/boo.vue'

export default{
    data(){
        return{
              countNumber: 0,
              messageToComponent:'daddy~',
              isFalse:false,
        };
    },
    components:{
        count,
        boo
    }
}
</script>

<template>
    <count :count=countNumber />
    <boo :message=messageToComponent :isTrue=isFalse />
</template>


<style>

</style>
