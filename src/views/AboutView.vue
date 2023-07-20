<script setup>
import CardNotif from '../components/CardNotif.vue';
</script>
<template>
  <div class="flex-row w-[390px] p-5">
    <a href="/" class=" inline-flex gap-2">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        stroke-width="1.5"
        stroke="currentColor"
        class="w-6 h-6"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          d="M19.5 12h-15m0 0l6.75 6.75M4.5 12l6.75-6.75"
        />
      </svg>

      <h1 class="text-red-500 font-semibold">Notification</h1>
    </a>
    <CardNotif/>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
