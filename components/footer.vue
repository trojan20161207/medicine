<template>
  <footer class="text-sm text-secondary-400">
    <div class="container mx-auto justify-center py-10 pb-10 text-center md:flex">
      <div>
        <NuxtLink
          :to="localePath('/')"
          class="font-display inline-flex items-center gap-2 text-lg font-bold text-secondary-700 transition-transform hover:text-primary-500 active:scale-95 md:text-xl">
          💊
          <div class="flex items-center gap-0.5">进口原研药目录</div>
        </NuxtLink>
        <p class="mt-2">约 400 种药品，实时更新的进口原研药数据库</p>
        <p class="mt-2">
          Made with
          <span class="text-red-500">❤️</span>
          by
          <a href="https://x.com/lvwzhen" target="_blank" class="underline underline-offset-2 hover:text-primary-500">
            lvwzhen
          </a>
        </p>
      </div>
    </div>
  </footer>
</template>

<script>

export default {
  name: "Footer",
  data() {
    return {};
  },
};
</script>
