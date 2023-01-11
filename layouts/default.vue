<template>
  <div>
    <h3>
      Меню
      <small>(находится в layouts/default.vue)</small>
    </h3>
    <ul>
      <li>
        <NuxtLink to="/">Главная</NuxtLink>
      </li>
      <li>
        <NuxtLink to="test">Тест</NuxtLink>
      </li>
    </ul>
    <slot/>
  </div>
</template>