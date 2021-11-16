<template>
  <div class="bg-gray-800 h-screen grid grid-cols-2"> 
        <div class="bg-gray-800">
         <div class="flex justify-center">
            <h1 class="text-center mt-10 flex items-center"> CALCULADORA <icon color='#33593d' size='25'></icon> </h1>
         </div>
         </div>

        
        <div class="bg-gray-800">
          <div class="flex justify-center">
            <h1 class="text-center mt-10 flex items-center"> HISTORIAL <icon2 color='#33593d' size='25'></icon2> </h1>
          </div>
          </div>
        
  </div>

</template>

<script>
import Icon from './components/assets/Icon.vue'
import Icon2 from './components/assets/Icon2.vue'
export default {
  components: {Icon, Icon2} 
}

</script>