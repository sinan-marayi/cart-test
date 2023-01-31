<template>
  <div class=" flex justify-between">
        <!-- cart -->
       <cartComponent @increaseBy="changeCount" :count = count :price=price></cartComponent>
        <!-- cart summary -->
       <cartSummary :total=total></cartSummary>
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
  },
  data(){
return{
  count:1,
  price:860,
  // total:0
}
  },
  methods:{
    changeCount(n){

      if(this.count ===1 && n===-1){
        return
      }
      this.count=this.count+n
    }
  },
  computed:{
    total(){
      return (this.count*this.price)
    }
  }
}
</script>

<style>

</style>
