<template>
  <div
    id="App"
    class="min-h-screen grid place-items-center bg-gradient-to-r from-cyan-500 to-blue-500"
  >
    <form
      @submit.prevent=""
      class="bg-slate-200 bg-opacity-80 py-10 px-16 rounded-2xl shadow-md"
    >
      <div class="mb-4">
        <h1 class="text-4xl font-bold text-center text-slate-700">Sign in</h1>
      </div>
      <div class="mt-10 grid gap-4">
        <input
          class="shadow appearance-none rounded-lg w-full py-3 px-6 text-gray-700 leading-tight focus:outline-none focus:shadow-outline"
          type="text"
          name="username"
          placeholder="Username"
          autocomplete="off"
        />
        <input
          class="shadow appearance-none rounded-lg w-full py-3 px-6 text-gray-700 leading-tight focus:outline-none focus:shadow-outline"
          name="password"
          type="password"
          placeholder="Password"
        />
      </div>
      <a
        href="#"
        class="text-slate-700 text-sm font-medium mt-4 block text-right"
        >Forgot password?</a
      >
      <div class="mt-8 flex items-center">
        <input
          class="mr-2 leading-tight focus:shadow-outline"
          type="checkbox"
          name="checkbox_name"
        />
        <label class="text-sm text-slate-700" for="checkbox_id">
          Remember me
        </label>
      </div>
      <button
        class="bg-slate-700 hover:bg-slate-500 transition-colors text-white px-4 py-2 rounded-md text-lg font-medium mt-8 w-full"
      >
        Sign in
      </button>
      <div class="mt-8 border-2 border-slate-400 p-4 rounded-lg text-sm">
        <p class="text-slate-700">
          Don't have an account?
          <a href="#" class="text-slate-700 font-medium">Sign up</a>
        </p>
      </div>
    </form>
  </div>
</template>
