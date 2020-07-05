<style>
  .tech {
    @apply text-red-600;
    @apply text-4xl;
    text-shadow: 1px 1px 1px #c33;
  }

  .plus {
    @apply text-2xl;
    @apply text-gray-800;
  }
</style>

<svelte:head>
  <title>Sapper SCSS and TailwindCSS project template</title>
</svelte:head>
<div
  class="flex flex-grow w-full min-h-screen items-center justify-center
  bg-orange-400">
  <div class="flex flex-col w-4/5 p-10 items-center">
    <span class="tech">Sapper</span>
    <span class="plus">+</span>
    <span class="tech">SCSS</span>
    <span class="plus">+</span>
    <span class="tech">TailwindCSS</span>
    <span class="text-4xl">💗</span>
  </div>
</div>
