<template>
    <div class="phone-page">
      <van-nav-bar title="联系电话" left-arrow @click-left="handlephone" />
    </div>
    <div>
        <van-button round block type="default" @click="handlephone">确定联系</van-button>
        
    </div>
  </template>
  
  <script setup>
  import { useRouter } from 'vue-router';
  
  const router = useRouter();
  
  function handlephone(){
    router.push('/phoneNumber')
  }
  
  </script>
  
  <style scoped>
  .logout-page {
    max-width: 400px;
    margin: 0 auto;
  }
  
  .logout-content {
    padding: 16px;
  }
  
  .logout-button-container {
    display: flex;
    justify-content: space-between;
    margin-top: 20px;
  }
  </style>
  