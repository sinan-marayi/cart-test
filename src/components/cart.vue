<template>
     <div class="cart flex h-60 basis-2/4 border border-gray-300 rounded-md mx-28 my-28">
            <div class="image w-1/4 ">
                <img class="h-52 w-52 m-4 rounded-md " src="https://images.unsplash.com/photo-1623428454614-abaf00244e52?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8d2VkZGluZyUyMGNha2VzfGVufDB8fDB8fA%3D%3D&w=1000&q=80" alt="">
            </div>
            <div class=" w-3/4 m-4 flex justify-between">
              <div class="index w-4/6 ml-1">
                <p class="font-semibold pb-1 text-lg">strawberry chocolate cake purple</p>
                <p class="text-gray-400">5 Kilograms</p>
                <p class="text-gray-400  pb-1">Rs. 860</p>
                  <div class="flex  mt-2">
                    <button  class="border border-gray-600 mx-2 px-2 rounded-full">-</button>
                    <p>3</p>
                    <button class="border border-gray-600 mx-2 px-2 rounded-full">+</button>
                  </div>
              </div>
              <span class=" w-1/6  relative">
                <p class="absolute top-0 right-0 font-medium ">5.0</p>
                <button class="absolute bottom-0 right-0 border border-gray -400 p-1 rounded">delete</button>
              </span>
            </div>
        </div>  
</template>

<script>

    export default{
        name: "cartComponent",
        components:{

        }
    }

</script>