<template>
    <HeaderComponent/>
    <main class="h-screen">
      main
    </main>
    <footer class="bg-blue-50 shadow ">
       footer
    </footer>
</template>

<script>
import HeaderComponent from "@/components/HeaderComponent";

export default {
  name: 'HomeView',
  components: {
    HeaderComponent

  }
}
</script>
