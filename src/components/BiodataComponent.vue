<template>
  <div class="biodata">
    <h2>Biodata</h2>
    <div class="text-container">
      <p>Nama: Azila Wandani</p>
      <p>Umur: 20 tahun</p>
      <p>Lokasi: Pekanbaru, Indonesia</p>
    </div>
    <div class="image-container">
    <img src= "foto.png" contain max-height="500"></div>
  </div>
</template>

<script>
export default {
  name: 'BiodataComponent'
};

</script>

<style>
.biodata {
  background-color: #7896f7;
  padding: 20px;
  margin-bottom: 20px;
  display: flex;
  align-items: center;
}

.biodata h2 {
  color: #333;
  font-size: 24px;
  margin-bottom: 20px;
}
.image-container {
  flex: 1;
  text-align: center;
}

.image-container img {
  border-radius: 50%;
  max-width: 200px;
}


.text-container {
  flex: 2;
  padding-left: 20px;
  display: flex;
  flex-direction: column;
}

.text-container p {
  margin-bottom: 10px;
}

.biodata p {
  margin-bottom: 10px;
}



</style>
