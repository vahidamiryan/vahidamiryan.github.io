<template>
  <div>
    <header>
      <nav>
        <ul>
          <li><NuxtLink to="/">About Me</NuxtLink></li>
          <li><NuxtLink to="/work">My Work</NuxtLink></li>
          <li><NuxtLink to="/skills">My Skills</NuxtLink></li>
          <li><NuxtLink to="/contact">Contact Me</NuxtLink></li>
        </ul>
      </nav>
    </header>
    <main>
      <slot />
    </main>
  </div>
</template>
