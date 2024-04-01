<template>
  <button @click="handleButtonClick">Kontak</button>
</template>

<script>
export default {
  name: 'ButtonKontakComponent',
  methods: {
    handleButtonClick() {
    
      console.log('Tombol Kontak ditekan!');
    }
  }
};
</script>

<style scoped>
button {
  padding: 10px 20px;
  font-size: 16px;
  border: none;
  background-color: #007bff;
  color: white;
  cursor: pointer;
  position: fixed;
  bottom: 20px;
  right: 20px;
  z-index: 999; 
}

button:hover {
  background-color: #0056b3;
}
</style>
