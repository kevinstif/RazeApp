<template>
 <div>

   <v-form @submit="addPost">
     <v-container>
       <v-row>
         <v-text-field v-model="description" label="description"></v-text-field>
       </v-row>
       <v-btn type="submit">Publish</v-btn>
     </v-container>
   </v-form>
 </div>
</template>

<script>
export default {
  name: "add-post",
  data(){
    return{
      description:'',
    }
  },
  methods:{
    addPost(item){
      item.preventDefault();
      const newPost={
        id:1,
        description:this.description
      }
      this.$emit('add-post',newPost)
    }
  }
}
</script>

<style scoped>

</style>