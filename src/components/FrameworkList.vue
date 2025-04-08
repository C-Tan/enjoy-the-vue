<template>
  <div>
    <h1>Frameworks</h1>
    <ul>
      <li>Vue.js</li>
      <li>Angular</li>
      <li>React</li>
    </ul>
  </div>
  <LanguageList lang="JavaScript" />
</template>

<script>
import LanguageList from './LanguageList.vue';
export default {
  name: 'FrameworkList',
  components: {
    LanguageList,
  },
};
</script>

<style>
div {
  text-align: left;
}
</style>
