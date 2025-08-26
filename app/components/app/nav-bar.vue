<template>
  <div class="navbar bg-primary text-primary-content">
    <div class="navbar-start">
      <NuxtLink to="/" class="btn btn-ghost text-xl">
        My App
      </NuxtLink>
    </div>

    <div class="navbar-end">
      <AppThemeToggle />

      <a class="btn btn-accent">Sign In</a>
    </div>
  </div>
</template>
