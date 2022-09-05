<template>
  <div>
    Improve your front-end skills by building projects Scan the QR code to visit
    Frontend Mentor and take your coding skills to the next level

    <div class="attribution">
      Challenge by
      <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">
        Frontend Mentor
      </a>
      . Coded by <a href="https://isamu.dev">@isamudev</a>.
    </div>
  </div>
</template>

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
      href: '/favicon.ico',
      sizes: '32x32',
    },
  ],
})
</script>
