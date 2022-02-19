<script>

import count from './components/count.vue';
import boo from './components/boo.vue';
import TWDB from './components/TWDB.vue';
// true == login false == register
import userForm from './components/userForm.vue';
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
        TWDB,
        userForm
    }
}
</script>

<template>
    <user-form :loginOrRegister="true" />
</template>


<style>
#app{
    height:100%;
}
</style>
