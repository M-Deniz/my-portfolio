<template>
  <h1 class="text-neutural-100 text-xlarge" lg="text-3xl mt-2" font-bold>
    How I Became A Tech Geek
  </h1>

  <article class="posts-text">
    <div>
      <p mb-5 mt-10 text-justify class="text-large text-grey-300">
        In my early years, around the age of 5 or 6, I stumbled upon a discarded Commodore 64, accompanied by a handwritten booklet. Intriguing alien-like scripts filled its pages, resembling hieroglyphs. These, I soon discovered, were commands necessary for playing games on the system. The catch? No dedicated internal storage meant entering these commands each time—a unique introduction to computing constraints.
      </p>

      <img src="/images/commodore64.jpg">
      <figcaption class="text-neutural-300" mt-3 text-left>
        Commodore 64 - Release: 1984
      </figcaption>
    </div>

    <div>
      <p mb-5 mt-10 text-justify class="text-large text-grey-300">
        Subsequently, I resourcefully acquired a PlayStation 2 from discarded items, driven by my desire to engage with more contemporary games. Given my father's disapproval of such pastimes, obtaining the gaming console required a somewhat unconventional approach. Over the course of one to two years, I immersed myself in titles such as God of War, Metal Gear Solid, and Dirt Rally, thereby expanding my gaming repertoire.
      </p>

      <img src="/images/ps2.jpg">
      <figcaption class="text-neutural-300" mt-3 text-left>
        Playstation 2 - Release: 2000
      </figcaption>
    </div>

    <div>
      <p mt-10 text-justify class="text-large text-grey-300">
        During that period, my affinity for video games deepened. At the age of 7, my father provided me with an HP PC, akin to a spacecraft with 4 GB of RAM, an Intel Duo Core CPU, and a 500 GB HDD. While modest by today's standards, these specifications proved more than sufficient for my needs in 2007, shaping my early technological experiences.
      </p>
    </div>

    <div>
      <p mb-5 mt-10 text-justify class="text-large text-grey-300">
        In 2014, as games became more demanding my existing HP PC fell short. Determined to broaden my gaming experience within budget, I configured a new system with an Intel Core i7 4770k, GTX 980, 16 GB of RAM, and a terabyte HDD. This upgrade not only facilitated the play of newer titles but also sparked a heightened curiosity for computational capabilities.
      </p>

      <img src="/images/my-pc.jpg">
      <figcaption class="text-neutural-300" mt-3 text-left>
        My Custom PC
      </figcaption>
    </div>
  </article>

  <div class="posts-text" mt-5 text-left>
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
