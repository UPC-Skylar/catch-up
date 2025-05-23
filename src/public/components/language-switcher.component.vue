<script>
import {Button as PvSelectButton} from "primevue";

export default {
  name: "language-switcher",
  components: {PvSelectButton},
  data(){
    return {
      languages: ['en', 'es'],
    }
  }
}
</script>

<template>
  <pv-select-button v-model="$i18n.locale" :options="languages" class="uppercase"/>
</template>

<style scoped>

</style>