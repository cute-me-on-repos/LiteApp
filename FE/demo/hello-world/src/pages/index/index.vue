<template>
  <div class="container">
    <h1>
      hello world~
    </h1>
    <video width="400" controls>
      <source
        src="https://www.w3schools.com/html/mov_bbb.mp4"
        type="video/mp4"
      />
      <source
        src="https://www.w3schools.com/html/mov_bbb.ogg"
        type="video/ogg"
      />
      Your browser does not support HTML video.
    </video>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss">
.container {
  width: 100%;
  padding: 0 50px;
  background: green;
  h1 {
    font-size: 20px;
    font-weight: 600;
    color: orange;
  }
}
</style>
