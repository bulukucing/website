<template>
  <div class="container mx-auto px-4 mt-12 md:mt-0">
    <div class="md:h-screen md:grid md:place-content-center">
      <div class="max-w-prose mb-5 md:mb-8">
        <h1 class="text-2xl md:text-4xl text-center font-extrabold mb-2">
          Hello, I am Abdul Qirom AKA. Bulu Kucing, I loves doing code
          especially on web development
        </h1>
        <p class="text-lg md:text-xl text-center font-extralight">
          Front-end web developer
        </p>
      </div>
      <div class="max-w-prose mb-5 md:mb-8">
        <div class="mb-4">
          <h2 class="text-xl md:text-2xl text-center font-extrabold">
            Tech and Tools
          </h2>
        </div>
        <TechToolsList />
      </div>
      <div class="max-w-prose mb-5 md:mb-8">
        <div class="mb-4">
          <h2 class="text-xl md:text-2xl font-extrabold text-center">
            Social Media
          </h2>
        </div>
        <SocialMediaList />
      </div>
      <div class="max-w-prose">
        <div class="mb-2">
          <h3 class="text-xl md:text-2xl font-extrabold text-center">More</h3>
        </div>
        <div>
          <div class="flex gap-4 justify-center">
            <span class="text-md md:text-lg font-semibold">
              <NuxtLink to="/project">Project</NuxtLink>
            </span>
            <span class="text-md md:text-lg font-semibold">
              <NuxtLink to="/about">About</NuxtLink>
            </span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts"></script>
