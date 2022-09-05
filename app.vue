<template>
  <main>
    <div class="card">
      <img class="card__img" src="/img/qr-code.png" alt="QR Code" />

      <h1 class="card__title">
        Improve your front-end skills by building projects
      </h1>

      <p class="card__description">
        Scan the QR code to visit Frontend Mentor and take your coding skills to
        the next level
      </p>
    </div>
  </main>
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap');

html,
body,
#__nuxt,
main {
  @apply h-full w-full;
}

body {
  background-color: hsl(212, 45%, 89%);
  font-family: 'Outfit', sans-serif;
}

main {
  @apply flex items-center;
}

.card {
  @apply mx-auto flex w-80 flex-col gap-4 rounded-2xl bg-white p-5 text-center;

  &__img {
    @apply rounded-xl;
  }

  &__title {
    color: hsl(218, 44%, 22%);

    @apply text-2xl font-bold;
  }

  &__description {
    color: hsl(220, 15%, 55%);

    @apply text-base font-normal;
  }
}
</style>

<script lang="ts" setup>
useHead({
  htmlAttrs: {
    lang: 'en',
  },
  title: 'QR code component challenge on Frontend Mentor',
  titleTemplate: (title) => `${title} - @isamudev | Full Stack Developer`,
  meta: [
    {
      name: 'description',
      content:
        'This is a solution to the QR code component challenge on Frontend Mentor.',
    },
  ],
  link: [
    {
      rel: 'icon',
      type: 'image/png',
      href: '/favicon.png',
      sizes: '32x32',
    },
  ],
})
</script>
