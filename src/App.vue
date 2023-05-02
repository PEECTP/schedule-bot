<template>
  <with-premium-page></with-premium-page>
</template>

<script>
import {defineComponent} from "vue";
import WithoutPremiumPage from "@/components/without-premium-page.vue";
import WithPremiumPage from "@/components/with-premium.vue";

export default defineComponent({
  components: {WithPremiumPage, WithoutPremiumPage}
})
</script>

<style>
</style>
