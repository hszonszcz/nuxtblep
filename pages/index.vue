<template>
  <div>
    <h1>main page</h1>
    <p>cośtam wpisane</p>
    <ul>
      <li><nuxt-link to="/a">Strona A</nuxt-link></li>
      <li><nuxt-link to="/b">Strona B</nuxt-link></li>
      <li><nuxt-link to="/c">Strona C</nuxt-link></li>
      <li><nuxt-link to="/test-route/d">Strona D</nuxt-link></li>
    </ul>
  </div>
</template>

<script>
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage'
})
