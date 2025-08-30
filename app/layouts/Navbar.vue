<script setup>
import { ref } from 'vue'
import Logo from '~/assets/Logo.svg'  
const isOpen = ref(false)
const toggleMenu = () => { isOpen.value = !isOpen.value }
</script>

<template>
  <nav class="bg-white shadow-md fixed top-0 left-0 w-full z-50">
    <div class="max-w-7xl mx-auto px-4  lg:px-8">
      <div class="flex items-center justify-between h-16 lg:ml-30 lg:mr-30">
        <!-- Logo -->
        <div class="flex items-center">
          <img :src="Logo" alt="Company Logo" class="h-10 w-auto" />
        </div>

        <!-- Center Links -->
        <div class="hidden md:flex flex-1 justify-center items-center gap-8">
          <div class="relative group">
            <a class="text-gray-700 font-medium flex items-center gap-1 hover:text-blue-600" href="#services">
              Services
              <svg width="16" height="16"></svg>
            </a>
          </div>
          <a href="#process" class="text-gray-700 hover:text-blue-600 font-medium">About Us</a>
          <a href="#blog" class="text-gray-700 hover:text-blue-600 font-medium">Blog</a>
          <a href="#footer" class="text-gray-700 hover:text-blue-600 font-medium">Contact</a>
        </div>

        <!-- Right: Free Consultation Button -->
        <div class="hidden md:flex items-center">
          <h1 class="bg-[#00e85a] text-black font-semibold px-4 py-2 rounded-lg flex items-center gap-2 shadow hover:bg-[#00c94a] transition">
            <svg width="18" height="18" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" viewBox="0 0 24 24"><rect x="3" y="4" width="18" height="16" rx="2"/><path d="M16 2v4M8 2v4M3 10h18"/></svg>
            Free Consultation
          </h1>
        </div>

        <!-- Mobile Menu Button -->
        <div class="md:hidden flex items-center">
          <button @click="toggleMenu" class="text-gray-700 focus:outline-none p-2 rounded">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/>
            </svg>
          </button>
        </div>
      </div>
    </div>

    <!-- Mobile Menu -->
    <transition name="fade">
      <div v-if="isOpen" class="md:hidden fixed top-16 left-0 w-full bg-white shadow-lg z-50 px-4 pb-4 pt-2 space-y-3">
        <a href="#services" class="block text-gray-700 hover:text-blue-600 font-medium py-2" @click="isOpen = false">Services</a>
        <a href="#process" class="block text-gray-700 hover:text-blue-600 font-medium py-2" @click="isOpen = false">About Us</a>
        <a href="#blog" class="block text-gray-700 hover:text-blue-600 font-medium py-2" @click="isOpen = false">Blog</a>
        <a href="#footer" class="block text-gray-700 hover:text-blue-600 font-medium py-2" @click="isOpen = false">Contact</a>
        <a  class="block bg-[#00e85a] text-black font-semibold px-4 py-2 rounded-lg mt-2 text-center" @click="isOpen = false">Free Consultation</a>
      </div>
    </transition>
  </nav>
</template>
