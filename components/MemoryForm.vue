<template>
    <div class="form-container">
      <form>
        <div class="form-group">
          <label for="title" class="form-label">Title:</label>
          <InputText id="title" class="form-input" />
        </div>
  
        <div class="form-group">
          <label for="memory" class="form-label">Memory:</label>
          <Textarea id="memory" v-model="value" rows="5" cols="30" class="form-input"></Textarea>
        </div>
  
        <Button label="Upload"  />
      </form>
      lsss
    </div>
  </template>
  
  <style scoped>
  .form-container {
    max-width: 400px;
    margin: auto;
    margin-top: 20px;
    padding: 20px;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }
  
  .form-group {
    margin-bottom: 20px;
  }
  
  .form-label {
    display: block;
    margin-bottom: 5px;
    font-weight: bold;
    color: #333;
  }
  
  .form-input {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
    outline: none;
  }
  
  .form-button {
    background-color: #3490dc;
    color: #fff;
    padding: 10px 15px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
  }
  
  .form-button:hover {
    background-color: #2779bd;
  }
  </style>
  
  <script setup>
  import InputText from 'primevue/inputtext';
  import Textarea from 'primevue/textarea';
  import Button from 'primevue/button';
  </script>
  