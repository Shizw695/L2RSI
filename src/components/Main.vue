<script>
import Title from './sections/Title.vue'
import Abstract from './sections/Abstract.vue'
import Method from './sections/Method.vue'
import Qualitative_Place_Recognition_Results from './sections/Qualitative_Place_Recognition_Results.vue'
import BibTeX from './sections/BibTeX.vue'

export default {
  components: {
    Title,
    Abstract,
    Method,
    Qualitative_Place_Recognition_Results,
    BibTeX
  }
}
</script>

<template>
  <Title/>
  <Abstract/>
  <Method/>
  <Qualitative_Place_Recognition_Results/>
  <BibTeX/>
</template>
