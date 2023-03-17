<script lang="ts">
export default {
  methods: {
    playSound(sound_index: number) {
      const audio = new Audio(`./mp3/note${sound_index}.mp3`)
      audio.load()
      audio.play()
    }
  }
}
</script>

<template>
  <div class="container">
    <div class="home-wrapper">
      <img src="../assets/xylaphone.jpg" usemap="#image-map" />
      <map name="image-map">
        <area
          coords="673,10,752,3,957,378,866,393"
          shape="poly"
          @click.prevent="playSound(0)"
          class="add-pointer"
        />
        <area
          coords="589,34,664,25,843,386,751,398"
          shape="poly"
          @click.prevent="playSound(1)"
          class="add-pointer"
        />
        <area
          coords="502,60,578,49,720,385,623,395"
          shape="poly"
          @click.prevent="playSound(2)"
          class="add-pointer"
        />
        <area
          coords="409,83,486,73,605,385,512,397"
          shape="poly"
          @click.prevent="playSound(3)"
          class="add-pointer"
        />
        <area
          coords="310,108,388,95,481,392,392,404,397,404,392,404"
          shape="poly"
          @click.prevent="playSound(4)"
          class="add-pointer"
        />
        <area
          coords="215,131,295,121,363,396,270,408"
          shape="poly"
          @click.prevent="playSound(5)"
          class="add-pointer"
        />
        <area
          coords="112,152,190,147,235,396,144,410"
          shape="poly"
          @click.prevent="playSound(6)"
          class="add-pointer"
        />
        <area
          coords="3,180,89,172,119,395,23,413"
          shape="poly"
          @click.prevent="playSound(7)"
          class="add-pointer"
        />
      </map>
    </div>
  </div>
</template>

<style>
.home-wrapper {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 80vh;
}
</style>
