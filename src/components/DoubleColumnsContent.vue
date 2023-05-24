<template>
      <section>
            <div class="content">
                  <h2>{{ title }}</h2>
                  <slot />

            </div>
            <div class="image">
                  <img src="../assets/fire_1.jpg">
            </div>
      </section>
</template>
<script>
export default {
      props: {
            title: String,
            image: File,
      },
}
</script>

<style scoped>
section {
      display: grid;
      grid-template-columns: 40% 60%;
}

.image img {
      width: 100%;
      /* Force un ratio d'iamge 
      Attention ca deforme l image */
      aspect-ratio: 2/1;
      /* Replace l'image au centre sans la deforme */
      object-fit: cover;
}

.content {
      padding: 2rem;
}

.content p {
      margin: 1rem 0;
}
</style>