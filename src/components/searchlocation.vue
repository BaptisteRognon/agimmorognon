
<template>
  <div class="flex relative justify-center items-center z-1001 mx-6">
    <input
      v-model="input"
      type="text"
      placeholder="Search location"
      class="
        flex
        w-full
        h-14
        placeholder-gray-500
        text-gray-900
        flex-none
        border-2 border-indigo-200
        rounded-md
        text-sm
        mx-10
        p-2
        outline-none
        focus:border-indigo-500
      "
    />

    <div class="flex absolute right-0 text-base rounded-md bg-indigo-500 mr-3">
      <svg
        width="40"
        height="40"
        viewBox="0 -8 20 40"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M9.58341 17.5C13.9557 17.5 17.5001 13.9556 17.5001 9.58333C17.5001 5.21108 13.9557 1.66667 9.58341 1.66667C5.21116 1.66667 1.66675 5.21108 1.66675 9.58333C1.66675 13.9556 5.21116 17.5 9.58341 17.5Z"
          stroke="white"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        />
        <path
          d="M18.3334 18.3333L16.6667 16.6667"
          stroke="white"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        />
      </svg>
    </div>
  </div>
</template>


<script>
import { SearchIcon } from "@heroicons/vue/solid";

export default {
  components: {
    SearchIcon,
  },
};
</script>
