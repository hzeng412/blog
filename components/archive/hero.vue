<script setup lang="ts">
import { blogsPage } from '~/data'
</script>

<template>
  <div class="container mx-auto mb-5">
    <div class="grid grid-cols-1 sm:grid-cols-2 items-center">
      <div class="px-6">
        <h1 class="text-black dark:text-zinc-300 font-semibold leading-tight text-4xl md:text-5xl my-5">
          {{ $t('blogsPage.title') }}
        </h1>
        <p class="dark:text-zinc-300">
          {{ $t('blogsPage.description') }}
        </p>
      </div>
      <div class="px-6 justify-self-center">
        <div class="hidden sm:block col-span-3">
          <NuxtImg src="/images/blogs-paris.png" width="240" quality="50" class="rounded-md" />
        </div>
      </div>
    </div>
  </div>
</template>
