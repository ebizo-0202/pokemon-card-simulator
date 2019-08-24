<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">
        pokemon-card-simulator
      </h1>
      <h2 class="subtitle">
        My doozie Nuxt.js project
      </h2>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="button--green"
        >
          Documentation
        </a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey"
        >
          GitHub
        </a>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component
export default class TopPage extends Vue {
}
</script>