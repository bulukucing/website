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
        <div class="flex flex-row gap-2 flex-wrap justify-center font-mono">
          <!-- Sementara dulu
            di benerin lain waktu..
          -->
          <span
            class="bg-slate-800 text-sm text-gray-200 px-2 py-1 font-semibold rounded"
          >
            <Icon name="logos:html-5" class="mr-1 w-3 h-3" />
            HTML
          </span>
          <span
            class="bg-slate-800 text-sm text-gray-200 px-2 py-1 font-semibold rounded"
          >
            <Icon name="logos:css-3" class="mr-1 w-3 h-3" />
            CSS
          </span>
          <span
            class="bg-slate-800 text-sm text-gray-200 px-2 py-1 font-semibold rounded"
          >
            <Icon name="logos:javascript" class="mr-1 w-3 h-3" />
            Javascript
          </span>
          <span
            class="bg-slate-800 text-sm text-gray-200 px-2 py-1 font-semibold rounded"
          >
            <Icon name="logos:vue" class="mr-1 w-3 h-3" />
            VueJS
          </span>
          <span
            class="bg-slate-800 text-sm text-gray-200 px-2 py-1 font-semibold rounded"
          >
            <Icon name="logos:nuxt-icon" class="mr-1 w-3 h-3" />
            NuxtJS
          </span>
          <span
            class="bg-slate-800 text-sm text-gray-200 px-2 py-1 font-semibold rounded"
          >
            <Icon name="logos:linux-tux" class="mr-1 w-3 h-3" />
            Linux
          </span>
          <span
            class="bg-slate-800 text-sm text-gray-200 px-2 py-1 font-semibold rounded"
          >
            <Icon name="logos:git-icon" class="mr-1 w-3 h-3" />
            Git
          </span>
          <span
            class="bg-slate-800 text-sm text-gray-200 px-2 py-1 font-semibold rounded"
          >
            <Icon name="logos:visual-studio-code" class="mr-1 w-3 h-3" />
            VS Code
          </span>
        </div>
      </div>
      <div class="max-w-prose mb-5 md:mb-8">
        <div class="mb-4">
          <h2 class="text-xl md:text-2xl font-extrabold text-center">
            Social Media
          </h2>
        </div>
        <div class="flex flex-row flex-wrap gap-4 justify-center text-sm md:text-xl">
          <a
            href="https://github.com/bulukucing/"
            class="bg-violet-200 hover:bg-gray-600 py-3 px-4 text-center rounded-lg"
          >
            <Icon name="logos:github-icon"/>
          </a>
          <a
            href="#"
            class="bg-violet-200 hover:bg-gray-600 py-3 px-4 text-center rounded-lg"
          >
            <Icon name="logos:linkedin-icon"/>
          </a>
          <a
            href="https://www.facebook.com/abdul.qirom.323"
            class="bg-violet-200 hover:bg-gray-600 py-3 px-4 text-center rounded-lg"
          >
            <Icon name="logos:facebook"/>
          </a>
          <a
            href="https://www.instagram.com/bulukucing_bk/"
            class="bg-violet-200 hover:bg-gray-600 py-3 px-4 text-center rounded-lg"
          >
            <Icon name="logos:instagram-icon"/>
          </a>
        </div>
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
