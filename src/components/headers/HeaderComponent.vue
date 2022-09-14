<template>
  <header>
    <div class="shadow bg-teal-600 py-2">
      <div class="container mx-auto">
          <div class="flex">
            <router-link class="text-4xl px-6 py-4 items-center bg-blue-50 shadow shadow-black rounded-md" to="/">
              Home
            </router-link>
            <div class="ml-5 flex items-center">
              <a class="text-2xl px-4 py-1 mx-2 justify-center bg-blue-50 shadow shadow-black rounded-md" href="Store">
                Store
              </a>
              <a class="text-2xl px-4 py-1 mx-2 justify-center bg-blue-50 shadow shadow-black rounded-md" href="/catalog">
                Catalog
              </a>
            </div>
            <div class="items-center bg-blue-50 shadow-black rounded-md ml-auto">
                <div class="items-center px-3 py-1">
                  <a class="px-2 text-3xl " href="/login">
                    Login
                  </a>
                </div>
                <div>
                  <router-link class="px-2 text-blue-400 drop-shadow shadow-black" to="/register">
                    Registration
                  </router-link>
                </div>
            </div>
          </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent"
}
</script>

<style scoped>

</style>