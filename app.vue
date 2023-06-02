<template>
  <div class="container px-8 sm:mx-auto w-full max-w-screen-md mt-8 md:mt-40">
    <div class="mb-8">
      <Theme />
    </div>
    <div class="flex items-center flex-wrap gap-4 text-slate-800 dark:text-white mb-10 text-md">
      <NuxtLink 
        to="/" 
        class="flex items-center gap-1 font-medium">
        <span class="text-cyan-500 dark:text-cyan-300">01.</span>
        <span>Home</span>
      </NuxtLink>
      <NuxtLink 
        to="/about" 
        class="flex items-center gap-1 font-medium">
        <span class="text-cyan-500 dark:text-cyan-300">02.</span>
        <span>About</span>
      </NuxtLink>
      <NuxtLink 
        to="/" 
        class="flex items-center gap-1 font-medium">
        <span class="text-cyan-500 dark:text-cyan-300">03.</span>
        <span>Contact</span>
      </NuxtLink>
    </div>
    <NuxtPage />
  </div>
  
</template>

<style>
.page-enter-active,
.page-leave-active {
  transition: all 0.25s;
}

.page-enter-from {
  opacity: 0;
  transform: translateY(-4px);
}

.page-leave-to {
  opacity: 0;
  transform: translateY(4px);
}

body {
  font-family: Inter;
  /* background: #f3f4f6; */
  background-image: linear-gradient(to right top, #ffffff, #fdfdfd, #fbfbfc, #f8f9fa, #f6f7f8, #f6f7f8, #f6f7f8, #f6f7f8, #f8f9fa, #fbfbfc, #fdfdfd, #ffffff);
  min-height: 100vh;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.dark body {
  /* background: #050505 #1F1E20; */
  background-image: linear-gradient(
    to right top,
    #050505,
    #0c0c0d,
    #111112,
    #161517,
    #1a191b,
    #1a191b,
    #1a191b,
    #1a191b,
    #161517,
    #111112,
    #0c0c0d,
    #050505
  );
  background-attachment: fixed;
}
</style>
