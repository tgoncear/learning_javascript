<template>
  <div>
    <p>{{counter}}</p>
    <button @click="incrementar">+</button>
    <button @click="decrementar">-</button>
  </div>
</template>
<script>
export default {
  data: function () {
    return {
      counter: 0
    }
  },
  methods: {
    incrementar(){
      this.counter++;
    },
    decrementar(){
      this.counter--;
    }
  }
}
</script>