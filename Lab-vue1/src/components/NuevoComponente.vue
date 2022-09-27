<template>
    <h1>Ramon!</h1>
    
    <div>
    <button v-on:click="wuTangClan">Function Expression</button>

    <button v-on:click="wuTangClan2">Function Declaration</button>
    </div>

</template>

<script setup>
import { ref } from "vue";



//function expression
function wuTangClan() {
    console.log("Wutang is for the children");
    alert("Wutang is for the children")
}





//function declaration
const wuTangClan2 = () => {
      console.log("Wutang is for the children");
    alert("Wutang is for the children")
    
}



</script>

<style>

    button{
        padding:1rem 2rem;
        border-radius: 10px;
        
    }

    button:nth-child(even){
        margin-left: 2rem;
    }

    </style>