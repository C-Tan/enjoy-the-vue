<template>
  <div>
    <h1>Pages</h1>
    <ul>
      <li>Login</li>
      <li>Home</li>
      <li>Toegewezen rapportages</li>
      <li>Uitgevoerde rapportages openen</li>
      <li>Kennisbase/documentatie</li>
      <li>Instellingen/beheer</li>
    </ul>
  </div>
</template>

<script>
  export default {
    name: 'PageList',
    props: {
      lang: {
        type: String,
        required: true,
      },
    },
  }
</script>

<style>
div {
  text-align: left;
}
</style>
