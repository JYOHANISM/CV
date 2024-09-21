<template>
  <div class="min-h-screen flex items-center justify-center bg-gradient-to-r from-blue-500 to-purple-700">
    <div class="container mx-auto text-center px-4 py-12">
      <!-- Profile Section -->
      <div class="bg-white shadow-lg rounded-lg p-8">
        <!-- Profile Image -->
        <div class="relative inline-block mb-6">
          <img 
            class="w-32 h-32 rounded-full mx-auto ring-4 ring-white" 
            src="@/assets/profile.jpg"
            alt="Profile Picture" 
          />
        </div>

        <!-- Profile Information -->
        <h1 class="text-4xl font-bold text-gray-800 mb-4">Halo! Saya Muchamad Farrel Ariza!</h1>
        <p class="text-gray-600 mb-6">Umur 19 Tahun | Mahasiswa Teknologi Informasi di Universitas Brawijaya</p>

        <!-- Social Media Links -->
        <div class="flex justify-center space-x-4">
          <a href="https://instagram.com/@farrelarizu" class="text-gray-800 hover:text-pink-500">
            <font-awesome-icon :icon="['fab', 'instagram']" />
          </a>
          <a href="https://id.linkedin.com/in/muchamad-farrel-ariza-93136a289" class="text-gray-800 hover:text-blue-700">
            <font-awesome-icon :icon="['fab', 'linkedin']" />
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomePage",
}
</script>

<style scoped>
/* Optional: Custom styling if needed */
</style>
