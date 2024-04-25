<template>
    <div class="back-ground">
      <h1>Collapsable Button with Static Text</h1>
      <div>
      <button class="expand-collapse-button" @click="toggleExpanded"  :aria-expanded="isExpanded">
      Toggle
    </button>
    <div v-show="isExpanded">
      <!-- Content to expand/collapse -->
      <p>One of our most comfortable seating collections, Turner makes the most of its handsome proportions, high supportive back, and plush cushions. The sofa is crafted in your choice of seat depth and width, a broad range of durable, supple leathers, and with or without nailhead trim</p>
    </div>
    </div>
    </div>
  
  </template>
  <script>
  export default {
    name: 'AccordionButton',
    data() {
      return {
        isExpanded: false
      }
    },
    methods: {
        toggleExpanded() {
          this.isExpanded = !this.isExpanded;
        }
      }
  }
  </script>
  <style scoped>
  p {
  background-color: white;
  padding: 15px;
  }
  .back-ground {
    background-color: rgb(241, 237, 237);
    padding: 10px;
    margin: 10px;
  }
  .expand-collapse-button {
    cursor: pointer;
    padding: 8px 16px;
    background-color: #007bff;
    color: #fff;
    border: none;
    border-radius: 4px;
  }
  </style>
  
  
  
  