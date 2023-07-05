<template>
    <ul>
        <li v-for="item in items" :key="item.id">{{ item.name }}  {{ item.age }}</li>
    </ul>
</template>

<script>
export default {
  data() {
    return {
      items: [
        { name: "Thanush", age: 20, id: 1 },
        { name: "Sri", age: 18, id: 2 },
        { name: "Eswar", age: 20, id: 3 },
      ],
    };
  },
};
</script>

<style scoped></style>
