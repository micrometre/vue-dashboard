<script setup lang="ts">
import FileUpload from './FileUpload.vue';
defineProps({
  title: {
    type: String,
    default: "",
  },
});
</script>

<template>
  <div class="flex flex-col flex-wrap sm:flex-row">
    <div class="w-full sm:w-1/2 xl:w-1/3">
      <div class="mb-4">
        <div class="w-full rounded-2xl bg-white p-4 shadow-lg">
          <div class="mb-6 flex items-center justify-between">
            <div class="flex items-center">
              <div class="flex flex-col">
                <span class="ml-2 font-bold text-black">
                  Upload Video
                </span>
              </div>
            </div>
          </div>
        </div>
      </div>
              <FileUpload />
    </div>
  </div>
</template>
