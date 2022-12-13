<template>
  <div>
    <div class="container mx-auto px-4">
      <div class="h-screen grid place-content-center">
        <div class="max-w-prose mb-8">
          <h1 class="text-2xl md:text-4xl font-extrabold mb-2">Hello, I am Abdul Qirom AKA. Bulu Kucing, I loves doing code especially on web development</h1>
          <p class="text-lg md:text-xl md:text-center font-light">Front-end web developer | Currently interest on learning back-end web development</p>
        </div>
        <div class="mb-8">
          <h2 class="text-xl md:text-2xl text-center font-extrabold mb-4">Tech Were i Use :</h2>
          <div class="flex flex-row flex-wrap gap-3 text-sm md:text-md text-center justify-center">
            <span class="bg-slate-800 text-gray-200 px-2 py-1 font-semibold rounded">
              <Icon name="logos:javascript" class="mr-1 w-3 h-3"/>
              Javascript
            </span>
            <span class="bg-slate-800 text-gray-200 px-2 py-1 font-semibold rounded">
              <Icon name="logos:vue" class="mr-1 w-3 h-3"/>
              VueJS
            </span>
            <span class="bg-slate-800 text-gray-200 px-2 py-1 font-semibold rounded">
              <Icon name="logos:nuxt-icon" class="mr-1 w-3 h-3"/>
              NuxtJS
            </span>
            <span class="bg-slate-800 text-gray-200 px-2 py-1 font-semibold rounded">
              <Icon name="logos:git-icon" class="mr-1 w-3 h-3"/>
              Git
            </span>
            <span class="bg-slate-800 text-gray-200 px-2 py-1 font-semibold rounded">
              <Icon name="logos:visual-studio-code" class="mr-1 w-3 h-3"/>
              VS Code
            </span>
          </div>
        </div>
        <div class="mb-8">
          <div class="mb-2">
            <h2 class="text-xl md:text-2xl text-center font-extrabold">More :</h2>
          </div>
          <nav class="flex flex-row gap-4 text-lg lg:text-xl font-semibold justify-center">
            <span>
              <NuxtLink to="/projects">Projects</NuxtLink>
            </span>
            <span>
              <NuxtLink to="/contact">Contact</NuxtLink>
            </span>
            <span>
              <NuxtLink to="/about">About</NuxtLink>
            </span>
          </nav>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts"></script>