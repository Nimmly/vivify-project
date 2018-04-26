<template>
  <div class='container'>
    <div class ='row'>
      <div class ='col'>
        <ContactList />
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
  }

}
</script>

<style>

</style>
