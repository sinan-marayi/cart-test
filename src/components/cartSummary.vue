<template>
     <div class="total shadow-lg  basis-1/4 p-0  p-4 rounded-md border m-28 flex grid gap-y-4">
            <span class=" grid grid-cols-3 m-4 pb-4 border-b border-slate-200">
              <p class="col-span-2">strawberry chocolate cake purple</p><p class=" grid justify-items-end">Rs. {{total}}</p>
              <p class="col-span-3 text-gray-400">5 Kilograms</p>
            </span>
            <span class="priceSummary grid grid-cols-3 m-4 leading-loose">
              <p class="col-span-3 font-semibold ">Price summary</p>
              <p class="col-span-2">Subtotal</p><p class="grid justify-items-end">Rs.{{ total }} </p>
              <p class="col-span-2">Total</p><p class="grid justify-items-end">Rs.{{ total }} </p>
            </span>
            <button class="font-semibold rounded-lg bg-pink-400 items-end h-16 m-4">checkout</button>
        </div>   
</template>


<script>

    export default{
        name: "cartSummary",
        component:{
            
        },
        props:{
          total:Number
        },
        mounted(){
          console.log(this.total)
        }
        
    }

</script>