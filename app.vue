<template>
  <main>
    <div class="card">
      <img class="card__img" src="/img/qr-code.png" alt="QR Code" />

      <div class="card__body">
        <h1 class="card__title">
          Improve your front-end skills by building projects
        </h1>

        <p class="card__description">
          Scan the QR code to visit Frontend Mentor and take your coding skills
          to the next level
        </p>
      </div>
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
  @apply flex items-center justify-center;
}

.card {
  @apply flex w-80 flex-col gap-6 rounded-2xl bg-white p-4 text-center;

  &__img {
    @apply rounded-xl;
  }

  &__body {
    @apply flex flex-col gap-4;
  }

  &__title {
    color: hsl(218, 44%, 22%);

    @apply text-2xl font-bold leading-7;
  }

  &__description {
    color: hsl(220, 15%, 55%);
    font-size: 1.063rem;

    @apply pb-5 font-normal leading-5;
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
