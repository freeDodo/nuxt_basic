<template>
  <div id="app">
    <div id="container">
      <header class="header">
        <div class="header__logo">
          <h1>
            <NuxtLink to="/"> </NuxtLink>
          </h1>
        </div>
        <nav class="header__layout--nav primary">
          <NuxtLink to="/">Home</NuxtLink>
          <NuxtLink to="/nuxt/basic">page1</NuxtLink>
          <NuxtLink to="/nuxt/1">page2</NuxtLink>
        </nav>
        <nav class="header__layout--nav">
          <NuxtLink to="/nuxt/2">other</NuxtLink>
        </nav>
      </header>
      <router-view class="main" />
    </div>
  </div>
</template>

<style src="@/assets/css/layout.css">
</style>
