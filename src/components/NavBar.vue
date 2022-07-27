<template>
  <div class="flex justify-center bg-blue-600">
    <div class="lg:w-2/3 py-4 flex items-center justify-between text-white">
      <p>Download the wallet for desktop, mobile</p>
      <router-link to="/downloads" class="font-bold text-xl"
        >See options</router-link
      >
    </div>
  </div>
  <nav class="flex justify-center text-white bg-slate-900">
    <div class="lg:w-2/3 flex items-center justify-between py-4">
      <div>
        <router-link to="/" class="font-mono text-2xl">endeavr</router-link>
      </div>
      <div class="flex space-x-4 items-center">
        <router-link
          to="/dashboard"
          class="hover:bg-slate-800 p-3 w-40 text-center bg-slate-700"
          >Dashboard</router-link
        >
        <router-link
          to="/lapps"
          class="hover:bg-blue-900 p-3 w-40 text-center bg-blue-600"
          >Lightning Apps</router-link
        >
      </div>
    </div>
  </nav>
  <router-view />
</template>

<script></script>

<style></style>
