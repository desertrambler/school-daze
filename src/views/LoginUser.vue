<template>
  <main class="min-h-screen flex justify-center items-center bg-black">
    <div id="signupContainer" class="max-w-sm w-full bg-red-900 p-6 rounded-lg shadow-lg">
      <h2 class="text-3xl font-extrabold text-center mb-6">Login</h2>
      <form id="loginForm">
        <!-- Username -->
        <div class="mb-4">
          <label for="username" class="block text-lg font-medium text-gray-400 mb-2">Username</label>
          <input type="text" id="username" name="username" class="w-full p-3 border border-red-700 rounded-md focus:outline-none focus:ring-2 focus:ring-red-500 focus:border-red-500" required>
        </div>

        <!-- Password -->
        <div class="mb-6">
          <label for="password" class="block text-lg font-medium text-gray-400 mb-2">Password</label>
          <input type="password" id="password" name="password" class="w-full p-3 border border-red-700 rounded-md focus:outline-none focus:ring-2 focus:ring-red-500 focus:border-red-500" required>
        </div>

        <!-- Submit Button -->
        <div class="flex justify-center">
          <button type="submit"
          class="w-full py-3 bg-red-700 text-gray-400 font-bold rounded-md hover:bg-red-600 transition-colors duration-300">
            Log In
          </button>
        </div>
        <div class="flex justify-center mt-5">
          <button
            type="submit"
            id="signupButton"
            class="w-full py-3 bg-red-700 text-gray-400 font-bold rounded-md hover:bg-red-600 transition-colors duration-300">
            Sign Up
          </button>
        </div>
      </form>

      <!-- Forgot Password Link -->
      <div class="mt-4 text-center">
        <a href="#" class="text-sm text-black hover:text-gray-400">Forgot password?</a>
      </div>
    </div>
  </main>
</template>
