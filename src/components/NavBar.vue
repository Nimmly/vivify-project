<template>
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">

  <router-link class="navbar-brand" to="contacts">My Contacts</router-link>

  <div class="collapse navbar-collapse" id="navbarTogglerDemo03">
    <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
      <li class="nav-item">
        <router-link class="nav-link " to="contacts">Contacts</router-link>
      </li>
      <li class="nav-item">
      <router-link class="nav-link " to="add-contact">Add Contact</router-link>
      </li> 
    </ul>
  </div>
</nav>
</template>

<script>
export default {

}
</script>
