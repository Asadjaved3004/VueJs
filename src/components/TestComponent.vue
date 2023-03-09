<template>
    <div>

 
  <h1>Test Component</h1>
  
    </div>
 </template>
 
 <script>
 

 export default {
     name: 'TestComponent',
        props: {
         data: String,
         msg: String,
     },
 
     
    


 }
 </script>
 <style scoped>
 div{
     background-color: antiquewhite;
     height: 100px;
     width: 300px;
     padding: 42px;
     
 }
 </style>