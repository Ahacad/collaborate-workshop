<script setup lang="ts">
import { defineProps, ref } from "vue";

const props = defineProps({
  count: {
    default: 0,
  },
});

const counter = ref(props.count);

const getClass = (index: number) => {
  if (Number(counter.value) === 0) {
    return "text-white";
  }
  if (index + 1 === Number(counter.value)) {
    return "text-white";
  } else {
    return "text-gray-400";
  }
};

const items = [
  "Soft Skills",
  "All you need is GitHub",
  "Domain specific knowledge",
];
</script>

<template>
  <div>
    <ul>
      <li v-for="(item, key) in items" :key="key" :class="getClass(key)">
        <a :href="$slidev.nav.currentPage">
          {{ item }}
        </a>
      </li>
    </ul>
  </div>
</template>

