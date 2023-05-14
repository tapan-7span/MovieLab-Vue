<template>
  <div>
    <button class="border border-gray-200 hover:bg-gray-600 hover:text-white">
      {{ name }}
    </button>
  </div>
</template>
<script>
export default {
  props: {
    name: String,
  },
};
</script>
