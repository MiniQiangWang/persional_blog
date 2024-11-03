<template>
  <div class="about">
    <p>Using v-html directive: <span v-html="rawHtml"></span></p>
    <!-- <h1>This is an about page</h1> -->
  </div>
</template>

<script>
  const rawHtml = `<span style="color: red">This should be red.</span>`;

  export {
    rawHtml
  }

</script>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
