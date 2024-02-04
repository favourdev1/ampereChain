<template>
    <div class="icon-row">
      <HeroIcon name="medium" title="Medium" />
      <HeroIcon name="twitter" title="Twitter" />
      <HeroIcon name="reddit" title="Reddit" />
      <HeroIcon name="mail" title="Email" />
      <HeroIcon name="chat" title="Message" />
      <HeroIcon name="paper-airplane" title="Send" />
      
    </div>
  </template>
  
  <script>
  import { HeroIcon } from "@heroicons/vue";
  
  export default {
    components: {
      HeroIcon,
    },
  };
  </script>
  
  <style>
  .icon-row {
    display: flex;
    align-items: center;
    justify-content: space-around;
    background-color: black;
    padding: 10px;
  }
  
  .heroicon {
    fill: white;
  }
  </style>
  