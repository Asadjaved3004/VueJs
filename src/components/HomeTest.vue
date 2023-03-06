<template>
   <div>
 <h1 v-if="show">hello World</h1>
 <!-- <h1 v-else>hello World Block</h1> -->

 <h2> {{data}}</h2>
 <!-- <h2> {{msg}}</h2> -->
 <button v-on:click="display">Call hello Function</button>
 <button v-on:click="display">Toggle Button</button>
   </div>
</template>

<script>


export default {
    name: 'HomeTest',
    props: {
        data:{
            type: String,
        },
        msg: {
            type:String,
        }
    },methods:{
       //hello function
        display(){
            this.show=false
        }
    },data(){
        return {show:true}
    }
}
</script>
