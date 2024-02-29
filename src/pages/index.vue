<script setup lang="ts">
defineOptions({
  name: 'IndexPage',
})
</script>

<template>
  <section class="hero">
    <div class="hero__text">
      <div class="hero__text--wrapper">
        <h1 class="text-neutural-100 text-title text-align-left" font-bold>
          Deniz KAMILOGLU
        </h1>

        <p mt-2 class="text-align-left text-neutural-300 text-subtitle">
          Jr. Full-Stack Developer
        </p>

        <a href="/mustafa_deniz_kamiloglu_resume.pdf" target="_blank" download>
          <VIconButton align-icon-left icon="i-carbon-download-study" icon-size="text-xl" class="hero__cv">
            Download CV
          </VIconButton>
        </a>
      </div>
    </div>

    <img src="../../public/AvatarAndIcons.svg" class="hero__image" mx-auto max-w-170 w-full>
  </section>

  <section align-items grid mt-5 justify-center>
    <VIconCard class="experience h-[200px] w-[246px]" render-image align-icon-top>
      <span block class="text-medium">1 years as</span>
      <span block class="text-xlarge" font-bold>Developer</span>

      <template #icon>
        <img src="/icons/CodeIcon.svg" alt="adem" class="h-[80px] w-[80px]">
      </template>
    </VIconCard>

    <VIconCard class="experience h-[200px] w-[246px]" render-image align-icon-top mt-5 lg="mt-0 ml-40">
      <span block class="text-medium">1.5 years as</span>
      <span block class="text-xlarge" font-bold>DevOps</span>

      <template #icon>
        <img src="/icons/DesignIcon.svg" alt="adem" class="h-[80px] w-[80px]">
      </template>
    </VIconCard>
  </section>

  <section mt-10 lg="mt-25" class="aboutme__text">
    <h2 class="text-xlarge" font-bold>
      About Me
    </h2>

    <p mt-5 text-justify class="text-large text-grey-300">
      I am interested in the fields of Software Engineering, Full-Stack Development and System Management. Open to learning new things in order to further myself in the areas that I am interested in and with that I work with multiple clients around the globe, places like Sweden, Germany, United States of America. As a team-player I can easily establish a good communication with the people that I am working with. I have done my internships on relational databases such as SQL and ERP systems like SAP. I continue to work on different systems like Private Clouds and Highly Available cluster systems. I aim to improve myself more on Coding and Full-Stack Development.
    </p>
  </section>

  <section mt-10 lg="mt-25">
    <h2 class="text-xlarge" font-bold>
      Technologies That I Use
    </h2>

    <div grid grid-cols-4 mt-5 gap-8.5 lg="gap-10" class="technologies">
      <div class="tool-tip">
        <picture>
          <img src="/icons/Javascript.svg" class="hover-animation" rounded-lg>
        </picture>
        <span class="tool-tip-text">JavaScript</span>
      </div>
      <div class="tool-tip">
        <picture>
          <img src="/icons/TypeScript.svg" class="hover-animation" rounded-lg>
        </picture>
        <span class="tool-tip-text">TypeScript</span>
      </div>
      <div class="tool-tip">
        <picture>
          <img src="/icons/Vue.svg" class="hover-animation" rounded-lg>
        </picture>
        <span class="tool-tip-text">Vue</span>
      </div>
      <div class="tool-tip">
        <picture>
          <img src="/icons/React.svg" class="hover-animation" rounded-lg>
        </picture>
        <span class="tool-tip-text">React</span>
      </div>
      <div class="tool-tip">
        <picture>
          <img src="/icons/Nodejs.svg" class="hover-animation" rounded-lg>
        </picture>
        <span class="tool-tip-text">Node.js</span>
      </div>
      <div class="tool-tip">
        <picture>
          <img src="/icons/SCSS.svg" class="hover-animation" rounded-lg>
        </picture>
        <span class="tool-tip-text">SCSS</span>
      </div>
      <div class="tool-tip">
        <picture>
          <img src="/icons/HTML5.svg" class="hover-animation" rounded-lg>
        </picture>
        <span class="tool-tip-text">HTML5</span>
      </div>
      <div class="tool-tip">
        <picture>
          <img src="/icons/CSS3.svg" class="hover-animation" rounded-lg>
        </picture>
        <span class="tool-tip-text">CSS3</span>
      </div>
      <div class="tool-tip">
        <picture>
          <img src="/icons/TailwindCSS.svg" class="hover-animation" rounded-lg>
        </picture>
        <span class="tool-tip-text">TailwindCSS</span>
      </div>
      <div class="tool-tip">
        <picture>
          <img src="/icons/Postgres.svg" class="hover-animation" rounded-lg>
        </picture>
        <span class="tool-tip-text">Postgres</span>
      </div>
      <div class="tool-tip">
        <picture>
          <img src="/icons/Docker.svg" class="hover-animation" rounded-lg>
        </picture>
        <span class="tool-tip-text">Docker</span>
      </div>
      <div class="tool-tip">
        <picture>
          <img src="/icons/Github.svg" class="hover-animation" rounded-lg>
        </picture>
        <span class="tool-tip-text">Github</span>
      </div>
    </div>
  </section>

  <section mt-10 lg="mt-25">
    <h2 class="text-xlarge" font-bold>
      Let's Get In Touch
    </h2>

    <h3 class="text-secondary-500" mt-5>
      E-mail
    </h3>

    <div class="mx-auto max-w-fit overflow-hidden py-5">
      <div class="glow-animation">
        <a href="mailto:mustafa.deniz01@hotmail.com" target="_blank">
          mustafa.deniz01@hotmail.com
        </a>
      </div>
    </div>
  </section>
</template>

<route lang="yaml">
meta:
  layout: home
</route>
