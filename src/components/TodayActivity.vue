<template>
  <div class="my-4">
    <h1 class="text-lg font-semibold">Today's Activity</h1>
    <div class="flex mx-5 my-2 gap-20 ">
      <div class="flex flex-col items-center space-y-1">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke-width="1.5"
          stroke="currentColor"
          class="w-8 h-8 stroke-red-500"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M12 6v6h4.5m4.5 0a9 9 0 11-18 0 9 9 0 0118 0z"
          />
        </svg>
        <p class="text-sm font-medium">08:00</p>
        <p class="text-xs">Check In</p>
      </div>
      <div class="flex flex-col items-center space-y-1">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke-width="1.5"
          stroke="currentColor"
          class="w-8 h-8 stroke-red-500"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M16.023 9.348h4.992v-.001M2.985 19.644v-4.992m0 0h4.992m-4.993 0l3.181 3.183a8.25 8.25 0 0013.803-3.7M4.031 9.865a8.25 8.25 0 0113.803-3.7l3.181 3.182m0-4.991v4.99"
          />
        </svg>

        <p class="text-sm text-red-500 font-medium">03:00:00</p>
        <p class="text-xs">Working Hours</p>
      </div>
      <div class="flex flex-col items-center space-y-1">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke-width="1.5"
          stroke="currentColor"
          class="w-8 h-8 stroke-red-500"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M9 12.75L11.25 15 15 9.75M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
          />
        </svg>

        <p class="text-sm  font-medium">--:--</p>
        <p class="text-xs">Check Out</p>
      </div>
    </div>
  </div>
</template>
