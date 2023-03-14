<template>
    <div>

 
  <h1>Products Component</h1>
  
    </div>
 </template>
 
 <script>
 

 export default {
     name: 'ProductsComponent',
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
     margin: 20px;
     align-items: center;
     display: flex;
     justify-content: center;
 }
 </style>