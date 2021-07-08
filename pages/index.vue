<template>
  <div id="wrapper">
    <app-sidebar></app-sidebar>
    <div id="content-wrapper">
      <div id="content">
        <app-header></app-header>
      </div>
    </div>
  </div>
</template>

<script>
import Sidebar from '../components/layouts/sidebar.vue'
import Header from '../components/layouts/header.vue'

export default {
  components : {
    'app-sidebar': Sidebar,
    'app-header' : Header
  }

}
</script>