<template>
  <div>
    <h1>Project</h1>
    <div class="button-group">
      <button @click="showWebUrl">Project embedded</button> | 
      <button @click="showImage">Staff</button>
    </div>
    <div v-if="isWebUrlVisible">
      <a :href="webUrl" target="_blank">{{ webUrl }}</a>
      <p v-if="isWebUrlVisible">This is the link to access the project embedded.(just want to try add link :)</p>
    </div>
    <div v-if="isImageVisible">
      <img :src="imageSrc" alt="Project Image" class="project-image" />
      <p v-if="isImageVisible">This is a picture when I am the staff of TalentShow2022 at Higashikawa Japan(I don't know what to add here).</p>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isWebUrlVisible: false,
      isImageVisible: false,
      webUrl: 'https://drive.google.com/drive/u/2/folders/1jFtnbRBJcfpCtS25j1U9DyAV7JpC4fbV',
      imageSrc: require('../assets/TalentShowPic7'),
    };
  },
  methods: {
    showWebUrl() {
      this.isWebUrlVisible = true;
      this.isImageVisible = false;
    },
    showImage() {
      this.isWebUrlVisible = false;
      this.isImageVisible = true;
    },
  },
};
</script>

<style scoped>
.button-group {
  margin-bottom: 20px;
}

.project-image {
  max-width: 300px;
  margin-top: 20px;
}
</style>