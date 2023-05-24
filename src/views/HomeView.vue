<template>
  <main>
    <videoComponents />
    <WelcomeComponent />
    <DoubleColumnsContent title="Titre du premier composant">
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nemo asperiores accusamus, eligendi modi explicabo sit!
      </p>
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nemo asperiores accusamus, eligendi modi explicabo sit!
      </p>
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nemo asperiores accusamus, eligendi modi explicabo sit!
      </p>
    </DoubleColumnsContent>
    <DoubleColumnsContent title="Titre du 2e composant">
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nemo asperiores accusamus, eligendi modi explicabo sit!
      </p>
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nemo asperiores accusamus, eligendi modi explicabo sit!
      </p>
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nemo asperiores accusamus, eligendi modi explicabo sit!
      </p>
    </DoubleColumnsContent>
  </main>
</template>
<script >
import videoComponents from '../components/VideoComponents.vue'
import WelcomeComponent from '../components/WelcomeComponents.vue'
import DoubleColumnsContent from '../components/DoubleColumnsContent.vue'
import ImageRestaurant1 from '../assets/fire_1.jpg'
import ImageRestaurant2 from '../assets/fire_2.jpg'
import ImageRestaurant3 from '../assets/fire_3.jpg'

export default {
  components: { videoComponents, WelcomeComponent, DoubleColumnsContent }
}
</script>
