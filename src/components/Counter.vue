<template>
  <div>
    <h2>Contador: {{ count }}</h2>
    <button @click="increment">➕</button>
    <button @click="decrement">➖</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      count: 0,
    };
  },
  methods: {
    increment() {
      this.count++;
    },
    decrement() {
      this.count--;
    },
  },
};
</script>
