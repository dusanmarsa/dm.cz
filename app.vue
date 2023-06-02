<template>
  <div class="container px-8 sm:mx-auto w-full max-w-screen-md py-8 md:pt-40">
    <div class="mb-8">
      <Theme />
    </div>
    <div>
      <Heading custom-class="font-extrabold">
        <h1 class="select-none">Dušan Marsa 👨‍💻</h1>
      </Heading>
      <p>
        <strong>TypeScript developer</strong> - based in the
        <b>Czech Republic</b>, working <b>Remote</b>.
      </p>
      <p>
        I started my journey by building few static websites in HTML, CSS and
        have since developed a passion for TypeScript and Fullstack development.
        And I am trying to keep up-to-date by reading articles online, following
        much more experienced developers, and subscribing to bunch of
        newsletters.
      </p>
      <p>
        I am open with technologies that I need to use, there is always the
        right one for the specific task. But currently I stick with the proven
        few, such as <b>TypeScript</b>, <b>React</b>, and<b>Next.js</b>.
      </p>
      <p>
        <Heading>
          <h3>Looking for me?</h3>
        </Heading>
        Sometimes I am at
        <Button to="https://www.linkedin.com/in/dusanmarsa/" target="_blank"
          >LinkedIn</Button
        >, sometimes browsing through
        <Button to="https://github.com/dusanmarsa" target="_blank"
          >Github</Button
        >, and you can reach me on
        <Button to="mailto:dusanmarsa99@gmail.com"
          >Gmail (dusanmarsa99@gmail.com)</Button
        >
        too. Just please don't drop by my house unannounced - I'm probably in
        the zone!
      </p>
    </div>
  </div>
</template>

<!-- <div class="flex items-center flex-wrap gap-4 text-slate-800 dark:text-white mb-10 text-md">
      <NuxtLink 
        to="/" 
        class="flex items-center gap-1 font-medium">
        <span class="text-cyan-500 dark:text-cyan-300">01.</span>
        <span>Home</span>
      </NuxtLink>
      <NuxtLink 
        to="/coding" 
        class="flex items-center gap-1 font-medium">
        <span class="text-cyan-500 dark:text-cyan-300">02.</span>
        <span>Coding</span>
      </NuxtLink>
      <NuxtLink 
        to="/" 
        class="flex items-center gap-1 font-medium">
        <span class="text-cyan-500 dark:text-cyan-300">03.</span>
        <span>Contact</span>
      </NuxtLink>
  </div> -->

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
  background-image: linear-gradient(
    to right top,
    #ffffff,
    #fdfdfd,
    #fbfbfc,
    #f8f9fa,
    #f6f7f8,
    #f6f7f8,
    #f6f7f8,
    #f6f7f8,
    #f8f9fa,
    #fbfbfc,
    #fdfdfd,
    #ffffff
  );
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

h1 {
  font-size: 3.052rem;
  font-weight: bold;
  line-height: 48.83px;
}

h2 {
  font-size: 2.441rem;
  font-weight: bold;
  line-height: 39.06px;
}

h3 {
  font-size: 1.953rem;
  font-weight: bold;
  line-height: 31.25px;
}

h4 {
  font-size: 1.563rem;
  font-weight: bold;
  line-height: 25px;
}

p {
  @apply mt-4 text-slate-700 text-justify leading-loose dark:text-slate-400;
}

p > b {
  color: #334155;
}

p > strong {
  color: #1e293b;
}
.dark p > b {
  color: #cbd5e1;
}

.dark p > strong {
  color: #cbd5e1;
}
</style>
