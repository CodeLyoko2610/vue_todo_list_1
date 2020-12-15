<template>
  <div id="app">    
    
  </div>
</template>

<script>


export default {
  name: 'App',
  components: {
    
  },
  data(){
    return {
      todos: [
        {
          id: 1,
          title: 'Todo 1',
          completed: false        
        },
        {
          id: 2,
          title: 'Todo 2',
          completed: false        
        },
        {
          id: 3,
          title: 'Todo 3',
          completed: false        
        },
        {
          id: 4,
          title: 'Todo 4',
          completed: false        
        },
      ]
    }
  }
}
</script>

<style>
  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
  body {
    font-family: Arial, Helvetica, sans-serif;
    line-height: 1.4;
  }
  .btn {
    display: inline-block;
    border: none;
    background: #555;
    color: #fff;
    padding: 7px 20px;
    cursor: pointer;
  }
  .btn:hover {
    background: #666;
  }
</style>
