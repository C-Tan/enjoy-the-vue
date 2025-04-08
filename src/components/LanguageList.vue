<template>
  <div>
    <h1>Languages</h1>
    <ul>
      <li>{{lang}}</li>
      <li>TypeScript</li>
    </ul>
  </div>
</template>

<script>
  export default {
    name: 'LanguageList',
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
