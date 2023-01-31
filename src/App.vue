<template>
  <div class=" flex justify-between">
        <!-- cart -->
       <cartComponent></cartComponent>
        <!-- cart summary -->
       <cartSummary></cartSummary>
    </div>
    
</template>

<script>
import './assets/tailwind.css';
import cartComponent from './components/cart.vue';
import cartSummary from './components/cartSummary.vue';

export default {
  name: 'App',
  components: {
    cartComponent,
    cartSummary
  }
}
</script>

<style>

</style>
