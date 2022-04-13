<template>
  <m-header></m-header>
  <tab></tab>
  <router-view></router-view>
</template>

<script>
import MHeader from '@/components/header/MHeader.vue'
import Tab from '@/components/tab/tab.vue'

export default {
  components: {
    MHeader,
    Tab
  }
}
</script>
