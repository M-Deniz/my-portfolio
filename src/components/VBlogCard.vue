<template>
  <section class="border-color-400 h-[130px] w-[310px]" mt-5 border rounded-lg text-center>
    <div mt-2 />

    <span>
      <slot name="title">
        VBlogCard
      </slot>
    </span>

    <hr mx-auto my-1 max-w-35 class="border-color-400">

    <div class="text-grey-300 text-small" mx-4 mt-2 text-justify>
      <span>
        <slot name="content">
          VBlogCard Text
        </slot>
      </span>
    </div>
  </section>
</template>
