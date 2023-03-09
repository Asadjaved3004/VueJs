<template>
   <div>
 <!-- <h1 v-if="show">hello World</h1>
 <h1 v-else>hello World Block</h1> -->

 <!-- <h2> asdasd</h2>
 <h2> {{msg}}</h2> -->

 <!-- <table border="1px"> 
    <tr>
        <td>Id</td>
        <td>Name</td>
        <td>Email</td>
    </tr> -->
<!--------Using For Loop--------------------->
<!--------v-for is directive----------------------->
    <!-- <tr v-for="user in users" :key="user.id">
        <td>{{ user.id }}</td>
        <td>{{user.name}}</td>
        <td>{{user.email}}</td>
    </tr>
 </table> -->
 <!-- <button v-on:click="display">Call hello Function</button>
 <button v-on:click="display">Toggle Button</button> -->


 <h1>Home Component</h1>
 <UsersTest/>
<TestComponent/>
   </div>
</template>

<script>

import UsersTest from './UsersTest.vue'
import TestComponent from './TestComponent.vue'
export default {
    name: 'HomeTest',
    components:{
    UsersTest,
    TestComponent,
    },
   
  
    props: {
        data: String,
        msg: String,
    },

    // },
    //     data(){
    //             return {
    //                  users:[
    //                     {id:1,name:'Asad',email:'asadjaved3004@gmail.com'},
    //                     {id:2,name:'Ali',email:'hjaved01@gmail.com'},
    //                     {id:3,name:'Fahad',email:'fakram@gmail.com'},
    //                     {id:4,name:'haseeb',email:'hjaved@gmail.com'},
    //                     {id:5,name:'Ismail',email:'ikiyani@gmail.com'},

    //                  ],
    //            }
    //     }
    // ,methods:{
    //    //hello function
    //     display(){
    //         this.show=false
    //     }
    // }
}
</script>
<style>
div{
    background-color: #dde5ec;
    height: 500px;
}
</style>