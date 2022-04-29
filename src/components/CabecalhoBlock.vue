<script>
export default {
  data() {
    return {
      items: ["dicas", "cuidados", "racoes", "tosa", "outros"],
    };
  },
};
</script>
<template>
  <header class="header">
    <ul>
      <li v-for="(item, i) of intems" :key="i">{{ item }}</li>
    </ul>
  </header>
</template>
