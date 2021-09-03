<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import Navbar from './components/Navbar.vue'
import Modal from './components/Modal1.vue'
import Modal2 from './components/Modal2.vue'
</script>

<template>
    <Navbar/>
    <div class="flex justify-center space-x-4 items-center">
      <div>
        <Modal/>
      </div>
      <div>
        <Modal2/>
      </div>
    </div>
</template>

<style>

</style>
