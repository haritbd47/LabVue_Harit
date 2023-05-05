<template>
   <v-container>
      <v-row class="text-center">
         <v-col cols="12">            
            <img
               src="../assets/JJpic2022.jpg"
               class="my-3"
               contain
               height="200"
            />
         </v-col>

         <!--<v-col class="mb-4">
            <h1 class="text-h3 font-weight-bold mb-3">Welcome to Vuetify</h1>

            <p class="subheading font-weight-regular">
               For help and collaboration with other Vuetify developers,
               <br />please join our online
               <a href="https://community.vuetifyjs.com" target="_blank"
                  >Discord Community</a
               >
            </p>
         </v-col>-->
              <v-col class="mb-4">
        <h1 class="text-h3 font-weight-bold mb-3">My Profile</h1>

        <p class="subheading font-weight-regular">
           Name: Harit Benjangkaprasert
        </p>
        <p class="subheading font-weight-regular">
           Age: 22
        </p>
        <p class="subheading font-weight-regular">
           Skills: Vue.js, SQL, C#, C++
           (very poor skills LOL)
        </p>
        <p class="subheading font-weight-regular">
           Currently study at TNI
        </p>
     </v-col>
      </v-row>
   </v-container>
</template>

<script>
export default {
   name: 'HelloWorld',

   data: () => ({
      
   })
}
</script>

