<template>
  <nav text-xl mt-6 inline-flex gap-2>
    <button class="icon-btn !outline-none" @click="toggleDark()">
      <div v-if="isDark" i-carbon-moon />
      <div v-else i-carbon-sun />
    </button>

    <a
      class="icon-btn"
      i-carbon-home
      rel="noreferrer"
      href="http://localhost:3333"
    />

    <a
      class="icon-btn"
      i-carbon-logo-github
      rel="noreferrer"
      href="https://github.com/Marshall-Sun/vue-starter"
      target="_blank"
      title="GitHub"
    />
  </nav>
</template>
