<template>
  <div class="blancof h-screen grid grid-cols-2"> 
      <div>
         <div class="flex justify-center">
            <h1 class="text-center mt-10 flex items-center font1 text-3xl The quick brown fox"> 
              <span class="mr-8 azuloscurof">CALCULADORA</span>
              <icon class="mb-2" color='#33593d' size='35'></icon> 
            </h1>
         </div>
     </div>

        
     <div class="flex flex-col"> 
         <div class="flex justify-center">
             <h1 class="text-center mt-10 flex items-center font1 text-3xl The quick brown fox">
               <span class="mr-8 azuloscurof">HISTORIAL</span>
                <div class="mb-2"> 
                 <icon2 color='#33593d' size='35'></icon2>
                </div>
             </h1>
         </div>
           <div class="flex justify-end items-end w-full flex-grow">
            <a href="">
              <icon3 class="mb-8 mr-10" color='#e63946' size='35'></icon3>
            </a>
           </div>
     </div>
        
  </div>

</template>

<script>
import Icon from './components/assets/Icon.vue'
import Icon2 from './components/assets/Icon2.vue'
import Icon3 from './components/Icon3.vue'
export default {
  components: {Icon, Icon2, Icon3} 
}

</script>