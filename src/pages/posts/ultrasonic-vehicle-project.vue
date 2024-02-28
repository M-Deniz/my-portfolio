<template>
  <h1 class="text-neutural-100 text-xlarge" lg="text-3xl mt-2" font-bold>
    Ultrasonic Vehicle Project
  </h1>

  <div class="mx-auto max-w-fit overflow-hidden pb-6 pt-15">
    <div class="glow-animation">
      <p class="text-neutural-100 text-large" lg="text-xl" font-bold>
        Coming Soon
      </p>
    </div>
  </div>

  <div class="posts-text" lg="mx-20" mx-10 mt-5 text-left>
    <div>
      <RouterLink to="/posts">
        <span>
          {{ ">" }}
        </span>
        <span text-left class="hover-text-animation">
          cd ..
        </span>
      </RouterLink>
    </div>

    <div mt-3>
      <RouterLink to="/">
        <span>
          {{ ">" }}
        </span>
        <span text-left class="hover-text-animation">
          cd ~
        </span>
      </RouterLink>
    </div>
  </div>
</template>

<route lang="yaml">
meta:
  layout: home
</route>
