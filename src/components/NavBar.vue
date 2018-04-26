<template>
<nav class="navbar navbar-expand-lg navbar-dark bg-primary">
  <router-link class="navbar-brand" to="contacts">My Contacts</router-link>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
      <router-link class="nav-item nav-link" to="contacts">Contacts</router-link>
      <router-link class="nav-item nav-link" to="add-contact">Add Contacts</router-link>
  </div>
</nav>
</template>