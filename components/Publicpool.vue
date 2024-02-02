<template>
    <div class="overflow-hidden bg-colorBgLight dark:bg-colorBgDark py-24 sm:py-32">
  <div class="mx-auto max-w-7xl px-6 lg:px-8">
    <div class="mx-auto grid max-w-2xl grid-cols-1 gap-x-8 gap-y-16 sm:gap-y-20 lg:mx-0 lg:max-w-none lg:grid-cols-2">
      <div class="lg:pr-8 lg:pt-4">
        <div class="lg:max-w-lg">
          <h2 class="text-base font-semibold leading-7 text-indigo-400">{{ $t("publicpool.preheader") }}</h2>
          <p class="mt-2 text-3xl font-bold tracking-tight text-gray-900 dark:text-white sm:text-4xl">{{ $t("publicpool.header") }}</p>
          <p class="mt-6 text-lg leading-8 text-gray-800 dark:text-white">{{ $t("publicpool.listitem3") }}</p>
          <dl class="mt-10 max-w-xl space-y-8 text-base leading-7 text-gray-800 dark:text-white lg:max-w-none">
            <div class="relative pl-9">
              <dt class="inline font-semibold text-gray-900 dark:text-white">

              </dt>
              <dd class="inline">{{ $t("publicpool.listitem1") }}</dd>
            </div>
            <div class="relative pl-9">
              <dt class="inline font-semibold text-gray-900 dark:text-white">

              </dt>
              <dd class="inline">{{ $t("publicpool.listitem2") }}</dd>
            </div>
            <div class="relative pl-9">
              <dt class="inline font-semibold text-gray-900 dark:text-white">

              </dt>
              <dd class="inline">{{ $t("publicpool.listitem3") }}</dd>
            </div>
          </dl>
        </div>
      </div>
      <img src="/project/blog-img/first-setup.jpg" alt="Product screenshot" class="w-[48rem] max-w-none rounded-xl shadow-xl ring-1 ring-white/10 sm:w-[57rem] md:-ml-4 lg:-ml-0" width="2432" height="1442">
    </div>
  </div>
</div>

</template>