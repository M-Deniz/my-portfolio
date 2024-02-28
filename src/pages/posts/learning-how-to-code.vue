<template>
  <h1 class="text-neutural-100 text-xlarge" lg="text-3xl mt-2" font-bold>
    Learning How To Code
  </h1>

  <article class="posts-text">
    <div>
      <p mb-5 mt-10 text-justify class="text-large text-grey-300">
        Back in August 2017 I started to study my bachelor degree in Istanbul - Halic University as a Computer Engineer. When I get in the academy, I didn't have any main purpose other than making Triple A video games when I graduate and get my place in the sector. Video games were not just a hobby for me but they were my main purpose to live, a passion that shaped my world. So I thought to myself "Well, I guess that'll be my main goal to achieve then...".
      </p>

      <img src="/images/halic-university.jpg">
      <figcaption class="text-neutural-300" mt-3 text-left>
        Halic University - Istanbul / Turkey
      </figcaption>
    </div>

    <div>
      <p mb-5 mt-10 text-justify class="text-large text-grey-300">
        Weeks evolved into months, and the relentless passage of time seemed akin to a fleeting breeze, while the academic challenges intensified with each passing day, particularly for me. Allow me to be candid—I do not lay claim to the brilliance of minds such as Einstein or Newton, and I harbor no inclination to feign such intellectual stature. It is evident that within the academic sphere, there existed individuals far more astute than myself. Despite not being the brightest tool in the shed, I found solace and zeal in my fervor for information technologies and coding—a passion not universally shared among my peers. This realization prompted me to acknowledge the selective nature of this field, recognizing that the intrinsic appeal of technology and coding may not resonate universally. In essence, it is an affinity reserved for individuals akin to myself—a fervent enthusiast in the realm of technology. While I successfully navigated most of the classes centered around coding, the more generalized engineering courses posed significant challenges, resulting in notable setbacks—a circumstance not unfamiliar to me.
      </p>
    </div>

    <div>
      <p mb-5 mt-10 text-justify class="text-large text-grey-300">
        During my second year at the university, I grappled with the challenges posed by both the courses I had previously failed and the introduction of new subjects, rendering the semester exceptionally demanding. The curriculum comprised two distinct categories of classes: general engineering studies encompassing disciplines such as Discrete Math, Signals & Systems, and even Electronic Circuits (borrowed from the Electrical Engineering Department), and specialized courses within our field, such as Data Structures & Algorithms and Automata Theory. While I navigated the field-specific courses with relative ease, the general engineering classes proved to be a formidable challenge, akin to a recurring nightmare for me.
      </p>
    </div>

    <div>
      <p mb-5 mt-10 text-justify class="text-large text-grey-300">
        As the culmination of four years rapidly approached, the realization of graduating from the academy induced a sense of astonishment at the swift passage of time. Reflecting upon my university years, a sense of nostalgia and longing for those formative experiences emerges. Yet, upon contemplating whether attending the academy was a necessary prerequisite for becoming a Computer Engineer, or more broadly, a proficient coder, I harbor reservations. In my assessment, an individual genuinely impassioned by the intricacies of computer technology need not necessarily rely on formal education. Such an individual, motivated by an innate curiosity and determination, would exhibit an unwavering commitment to learning, even in the face of seemingly insurmountable challenges within the realm of computer science.
      </p>
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
