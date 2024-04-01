<template>
  <div class="skill">
    <h2>Skill & Kemampuan</h2>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
      <li>Vue.js</li>
      <li>Database</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'SkillComponent'
};
</script>

<style scoped>
.skill {
  background-color: #7189ff;
  padding: 20px;
  margin-bottom: 20px;
}

.skill h2 {
  color: #333;
  font-size: 20px;
  margin-bottom: 10px;
}

.skill ul {
  list-style-type: none;
  padding: 0;
}

.skill li {
  margin-bottom: 5px;
}
</style>
