<template>
  <div id="app">
    <BiodataComponent />
    <SkillComponent />
    <PengalamanComponent />
    <ButtonKontakComponent />
  </div>
</template>

<script>
import BiodataComponent from './components/BiodataComponent.vue';
import SkillComponent from './components/SkillComponent.vue';
import PengalamanComponent from './components/PengalamanComponent.vue';
import ButtonKontakComponent from './components/ButtonKontakComponent.vue';

export default {
  name: 'App',
  components: {
    BiodataComponent,
    SkillComponent,
    PengalamanComponent,
    ButtonKontakComponent
  }
};
</script>

<style>
#app {
  font-family: Arial, sans-serif;
  padding: 20px;
  margin: 0;
  box-sizing: border-box;
  height: 100vh;
  background-size: cover;
  background-position: center;
}

h2 {
  margin-bottom: 10px;
  font-family: 'Arial', sans-serif;
  background-color: #f4f4f4;
  color: #333;
  line-height: 1.6;
  margin: 0;
  padding: 0;
}

ul {
  list-style-type: none;
  
}

li {
  margin-bottom: 5px;
  
}

button {
  padding: 10px 20px;
  font-size: 16px;
  border: none;
  background-color: #007bff;
  color: white;
  cursor: pointer;
}

button:hover {
  background-color: #0056b3;
  background-color: #333;
  color: #5d96bd;
  text-align: center;
  padding: 10px 0;
  position: fixed;
  bottom: 0;
  width: 100%;
}
img {
  width: 768px;
  height: 500px;

  
}
.bg-img {
  background-image: url('C:\Users\MSI CYBORG\Documents\Praktikum PBK\portofolio\public\foto.png');
  background-size: cover;
  background-position: left;
  height: 100vh;
}

</style>
