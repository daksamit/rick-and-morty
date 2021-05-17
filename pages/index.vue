<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">rick-and-morty</h1>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          Documentation
        </a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          GitHub
        </a>
        <a href="http://localhost:6006" target="_blank" class="button--pink">
          Storybook
        </a>
        <a
          href="http://localhost:3000/_tailwind"
          target="_blank"
          class="button--grey"
        >
          Tailwind Explorer
        </a>
      </div>
    </div>
  </div>
</template>

<script>
import { defineComponent, onMounted } from '@vue/composition-api'

export default defineComponent({
  setup() {
    onMounted(() => {
      console.log('mounted!')
    })
  },
})
</script>

<style>
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
