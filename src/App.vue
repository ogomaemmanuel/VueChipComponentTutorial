<template>
  <div id="app">
    <ChipInput v-model="selectedData" :selectList="chipData"></ChipInput>
  </div>
</template>

<script>

import ChipInput from "./components/ChipInput"
export default {
  name: 'app',
  components: {
    ChipInput
    
  },
  data(){
    return{
      selectedData:[],
 chipData: [
        {
          value: "1",
          text: "Root Access"
        },
        {
          value: "2",
          text: "Manage catlog"
        },
        {
          value: "3",
          text: "Manage reviews"
        },
        {
          value: "4",
          text: "Manage users"
        },
        {
          value: "5",
          text: "Manage administrators"
        },
        {
          value: "6",
          text: "Manage orders"
        },
        {
          value: "7",
          text: "Manage import"
        },
        {
          value: "8",
          text: "Manage import"
        },
        {
          value: "9",
          text: "Manage import"
        }
      ]
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
 
  margin-top: 60px;
}
</style>
