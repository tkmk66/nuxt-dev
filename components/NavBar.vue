<template>
<div>
  <nav>
    <nuxt-link to="/">Home</nuxt-link>
    <nuxt-link to="/about">About</nuxt-link>
    <nuxt-link :to="{ name: 'users-list' }">User</nuxt-link>
  </nav>
</div>
</template>
