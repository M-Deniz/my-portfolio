<template>
  <header>
    <nav class="navbar">
      <div flex items-center justify-between>
        <div>
          <RouterLink to="/">
            <img src="/images/my-logo-no-bg.png" h-9 w-14.5 lg="h-8.5 w-14">
          </RouterLink>
        </div>
        <div flex gap-5>
          <RouterLink to="/posts" class="hover-text-animation">
            <div i-carbon-blog lg="hidden" />
            <span hidden lg="block">
              Blog
            </span>
          </RouterLink>
          <RouterLink to="/projects" class="hover-text-animation">
            <div i-carbon-concept lg="hidden" />
            <span hidden lg="block">
              Projects
            </span>
          </RouterLink>
          <a icon-btn rel="noreferrer" href="https://github.com/M-Deniz" target="_blank" title="GitHub" class="hover-text-animation">
            <div i-carbon-logo-github />
          </a>
          <a icon-btn rel="noreferrer" href="https://www.linkedin.com/in/mustafa-deniz-kamilo%C4%9Flu-336870208/" target="_blank" title="Linkedin" class="hover-text-animation">
            <div i-carbon-logo-linkedin />
          </a>
        </div>
      </div>
    </nav>
  </header>
</template>

<route lang="yaml">
meta:
  layout: home
</route>
