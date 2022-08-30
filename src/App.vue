<template>
  <nav>
    <h4>menu (dans <code>/src/App.vue</code>)</h4>
    <ul>
      <li>
        <router-link to="/">
          lien vers
          <code>/src/pages/index.vue</code>
        </router-link>
      </li>
    </ul>
  </nav>

  <!-- Affiche les pages -->
  <router-view />
</template>
