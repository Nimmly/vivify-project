<template>
  <div class='container mt-4'>
    <div class ='row'>
      <div class ='col'>
        <ContactList :contacts='contacts'/>
      </div>
      <div class = 'col'>
        <ContactDetails />
      </div>
    </div>
  </div>
</template>

<script>
import ContactList from '../components/ContactList.vue'
import ContactDetails from '../components/ContactDetails.vue'

export default {
  components:{
    ContactList,
    ContactDetails
  },
  data(){
    return {
      contacts:[
        {name: 'john doe'},
        {name: 'jane doe'},
        {name: 'marko popovic'}
      ]
    }
  }

}
</script>

<style>

</style>
