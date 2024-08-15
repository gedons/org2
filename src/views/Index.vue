<template>
  <div class="flex flex-col min-h-screen">
    <!-- Header -->
    <header class="bg-green-600 text-white py-6 sm:py-8 shadow-lg">
      <div class="container mx-auto px-4">
        <div class="flex flex-col sm:flex-row sm:items-center sm:justify-between">
          <div>
            <h1 class="text-3xl font-bold mb-2 sm:mb-0">Welcome to My File Organizer</h1>
          </div>
          <div class="text-lg">
            <p>Organize, manage, and access your files and folders with ease</p>
          </div>
        </div>
      </div>
    </header>

    <main class="flex-1 bg-gray-100">
      <div class="container mx-auto px-4 py-12 sm:py-16">
        <section class="bg-white rounded-lg shadow-md p-8 sm:p-12">
          <h2 class="text-2xl font-semibold mb-4 text-gray-800">About This Site</h2>
          <p class="text-gray-600 mb-6">
            Our file organizer application allows you to efficiently manage your digital files and folders. With our intuitive interface, you can easily upload, create, delete, and organize your files and folders in a way that suits your needs. Whether you're working with documents, images, or other file types, our platform offers a seamless experience to keep everything in order.
          </p>
          <div class="text-gray-600">
            <p class="mb-4">Features include:</p>
            <ul class="list-disc pl-5">
              <li class="mb-2">File uploading with drag-and-drop functionality</li>
              <li class="mb-2">Folder creation and management</li>
              <li class="mb-2">File preview and access in various formats</li>
              <li class="mb-2">Secure authentication to protect your data</li>
              <li class="mb-2">Intuitive grid and list view options</li>
            </ul>
          </div>
          <!-- Get Started Button -->
          <div class="mt-6">
            <router-link to="/login" class="bg-yellow-300 text-black font-semibold py-2 px-6 rounded-md hover:bg-yellow-500 transition duration-200">
              Get Started
            </router-link>
          </div>
        </section>
      </div>
    </main>


    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-4 mt-8">
      <div class="container mx-auto px-4">
        <p class="text-center">&copy; 2024 My File Organizer. All rights reserved.</p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'Index',
};
</script>

<style scoped>
/* Custom styles can go here */
</style>
