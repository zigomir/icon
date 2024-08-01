<template>
  <Icon
    name="custom1:nuxt-v3"
    size="64"
    mode="svg"
  />

  <!--
    WORKAROUND: load at least one icon in css mode to make svg mode work.
    It doesn't even have to be the same icon
  -->
  <Icon
    style="display: none;"
    name="custom1:nuxt-v1"
    size="64"
    mode="css"
  />
</template>
