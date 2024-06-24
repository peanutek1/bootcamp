<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    Czesc!
  <br/>
  <button @click="podbij">podbij</button>
  {{ licznik }}
  </main>
</template>

<script>
export default{
  data() {
    return {
      licznik: 0
    }
  },
  methods: {
    podbij() {
      this.licznik++
    }
  }
}
</script>