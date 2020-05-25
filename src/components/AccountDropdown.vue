<template>
  <div class="relative">
    <button
      class="block h-8 w-8 rounded-full overflow-hidden border-2 border-gray-600 focus:outline-none focus:border-white"
    >
      <img
        class="h-full w-full object-cover"
        src="https://images.unsplash.com/photo-1537815749002-de6a533c64db?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1445&q=80"
        alt="Your avatar"
      />
    </button>
    <div class="absolute right-0 mr-2 mt-2 py-2 w-48 bg-white rounded-lg shadow-xl">
      <a
        href="#"
        class="block px-4 py-2 text-gray-800 hover:bg-indigo-500 hover:text-white"
      >Account settings</a>
      <a href="#" class="block px-4 py-2 text-gray-800 hover:bg-indigo-500 hover:text-white">Support</a>
      <a
        href="#"
        class="block px-4 py-2 text-gray-800 hover:bg-indigo-500 hover:text-white"
      >Sign out</a>
    </div>
  </div>
</template>

<script>
export default {};
</script>