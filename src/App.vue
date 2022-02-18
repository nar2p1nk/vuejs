<script>

import count from './components/count.vue';
import boo from './components/boo.vue'
import TWDB from './components/TWDB.vue'
export default{
    data(){
        return{
              countNumber: 0,
              messageToComponent:'daddy~',
              isFalse:false,
              dataToBind: 'type at the input to change me'
        };
    },
    components:{
        count,
        boo,
        TWDB
    }
}
</script>

<template>
    <count :count=countNumber />
    <boo :message=messageToComponent :isTrue=isFalse />
    <TWDB :data=dataToBind />
</template>


<style>

</style>
