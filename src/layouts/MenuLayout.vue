<template>
  <div>
    <div class="gnb">
      <ul>
        <li><router-link to="/">main</router-link></li>
        <li><router-link to="/menu">menu</router-link></li>
      </ul>
    </div>
    <slot></slot>
  </div>
</template>
