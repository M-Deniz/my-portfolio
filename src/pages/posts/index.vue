<template>
  <div class="text-neutural-100 text-xlarge" lg="text-3xl mt-2" font-bold>
    Blog
  </div>

  <hr mx-auto mb-5 mt-3 max-w-50 class="border-color-400">

  <ul text-left>
    <div grid justify-center gap-5>
      <RouterLink to="/posts/ultrasonic-vehicle-project">
        <li>
          <div>
            <span class="text-neutural-100 text-large hover-text-animation">
              Ultrasonic Vehicle Project
            </span>
          </div>
          <div>
            <span class="text-neutural-300">
              Details Coming Soon...
            </span>
          </div>
        </li>
      </RouterLink>

      <RouterLink to="/posts/learning-how-to-code">
        <li>
          <div>
            <span class="text-large text-neutural-100 hover-text-animation">
              Learning How To Code
            </span>
          </div>
          <div>
            <span class="text-neutural-300">
              Feb 27 • 10 min
            </span>
          </div>
        </li>
      </RouterLink>

      <RouterLink to="/posts/how-i-became-a-tech-geek">
        <li>
          <div>
            <span class="text-large text-neutural-100 hover-text-animation">
              How I Became A Tech Geek
            </span>
          </div>
          <div>
            <span class="text-neutural-300">
              Feb 22 • 5 min
            </span>
          </div>
        </li>
      </RouterLink>

      <RouterLink to="/">
        <span>
          {{ ">" }}
        </span>
        <span text-left class="hover-text-animation">
          cd ~
        </span>
      </RouterLink>
    </div>
  </ul>
</template>

<route lang="yaml">
meta:
  layout: home
</route>
