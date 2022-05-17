
<template>
  <div class="flex relative justify-center items-center z-1001 mx-6">
    <input
      v-model="input"
      type="text"
      placeholder="Search with Search Bar"
      class="
        flex
        w-full
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

    <div
      class="
        flex
        absolute
        right-0
        rounded-full
        text-base text-indigo-500
        bg-indigo-100
        w-5
        mr-4
      "
    >
      <ChevronDownIcon></ChevronDownIcon>
    </div>
  </div>
</template>


<script>
import { ChevronDownIcon } from "@heroicons/vue/solid";

export default {
  components: {
    ChevronDownIcon,
  },
};
</script>
