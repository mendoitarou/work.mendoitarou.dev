<script setup lang="ts">
import type { NavigationMenuItem } from '@nuxt/ui'

useHead({
  meta: [
    { name: 'viewport', content: 'width=device-width, initial-scale=1' }
  ],
  link: [
    { rel: 'icon', href: '/favicon.ico' }
  ],
  htmlAttrs: {
    lang: 'ja'
  }
})

const title = 'めんどい太郎のやってきたこと'
const description = 'めんどい太郎がこれまでやってきたことを紹介するページ'

useSeoMeta({
  title,
  description,
  ogTitle: title,
  ogDescription: description,
  ogImage: 'https://work.mendoitarou.dev/images/card-image.png',
  twitterImage: 'https://work.mendoitarou.dev/images/card-image.png',
  twitterCard: 'summary_large_image'
})

const navItems = ref<NavigationMenuItem[]>([
  {
    label: 'Home',
    icon: 'material-symbols-home-outline',
    to: '/'
  },
  {
    label: 'Works',
    icon: 'material-symbols-work-outline',
    to: '/works/'
  },
  {
    label: 'Categorys',
    icon: 'material-symbols-category-outline',
    to: '/works/categorys/',
    class: 'hidden'
  }
])
</script>

<template>
  <UApp>
    <UBanner icon="ic-outline-announcement" color="warning" title="コンテンツは順次追加予定です！" />
    <UBanner icon="i-lucide-info" title="めんどい太郎についてはホームページを参照してください。" to="https://mendoitarou.dev/" target="_blank" close />

    <UHeader>
      <template #title>
        <NuxtLink to="/">
          <b>めんどい太郎のやってきたこと</b>
        </NuxtLink>
      </template>

      <UNavigationMenu content-orientation="vertical" :items="navItems" class="w-full" />

      <template #right>
        <UColorModeButton />

        <UButton
          to="https://github.com/mendoitarou/work.mendoitarou.dev"
          target="_blank"
          icon="i-simple-icons-github"
          aria-label="GitHub"
          color="neutral"
          variant="ghost"
        />
      </template>

      <template #body>
        <UNavigationMenu orientation="vertical" content-orientation="vertical" :items="navItems" class="w-full" />
      </template>
    </UHeader>

    <UMain>
      <NuxtPage />
      <br>
    </UMain>

    <USeparator />

    <UFooter>
      <template #left>
        <p class="text-sm text-muted">
          Built with Nuxt UI • © {{ new Date().getFullYear() }} <ULink to="https://mendoitarou.dev/">mendoitarou_</ULink>
        </p>
      </template>

      <template #right>
        <UButton
          to="https://mendoitarou.dev/"
          target="_blank"
          icon="material-symbols-home"
          aria-label="HomePage"
          color="neutral"
          variant="ghost"
        />
        <UButton
          to="https://github.com/mendoitarou"
          target="_blank"
          icon="i-simple-icons-github"
          aria-label="GitHub"
          color="neutral"
          variant="ghost"
        />
      </template>
    </UFooter>
  </UApp>
</template>
