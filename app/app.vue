<template>
  <NuxtRouteAnnouncer />
  <div
    class="absolute inset-0 h-full w-full bg-black bg-[radial-gradient(#f7f4ec_1px,transparent_1px)] [background-size:16px_16px] [mask-image:radial-gradient(ellipse_60%_60%_at_50%_50%,#000_60%,transparent_100%)] -z-10" />
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>

<style>
body {
  background-color: black;
}
</style>