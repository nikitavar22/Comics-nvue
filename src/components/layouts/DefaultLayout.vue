<template>
  <HeaderComponent/>
  <main class="h-screen">
    <slot/>
  </main>
  <FooterComponent/>
</template>

<script>
import HeaderComponent from "@/components/headers/HeaderComponent";
import FooterComponent from "@/components/footers/FooterComponent";

export default {
  name: "DefautLayout",
  components: {FooterComponent, HeaderComponent}

}
</script>

<style scoped>

</style>