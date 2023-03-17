<script lang="ts">
export default {}
</script>

<template>
  <div class="container">
    <div class="about-wrapper">
      <h2 class="add-padding">Sample audio:</h2>
      <audio id="audio" src="./mp3/preview.mp3" controls></audio>
      <h2 class="add-padding">Assignment details:</h2>
      <img src="../assets/assignment.jpg" alt="" class="image-size" />
    </div>
  </div>
</template>

<style>
.about-wrapper {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  font-size: 1.5rem;
}
.image-size {
  width: 40%;
}

.add-padding {
  padding: 20px 0px 5px 0px;
}
</style>
