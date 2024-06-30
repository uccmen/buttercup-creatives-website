<template>
  <main class="grid lg:grid-cols-2 place-items-center pt-16 pb-8 md:pt-8">
    <div class="p-24 md:order-1 hidden md:block">
      <img
        class="rounded-full transition-transform transform hover:scale-125"
        src="~/assets/img/hero.jpg"
        alt="Bee on a buttercup flower"
        loading="eager"
        format="avif"
        width="512"
        height="512"
      />
    </div>

    <div>
      <h1 class="text-5xl lg:text-6xl xl:text-7xl font-bold lg:tracking-tight">
        Buttercup Creatives
      </h1>
      <h2 class="text-2xl lg:text-3xl xl:text-4xl text-slate-600">
        Transforming Ideas into Compelling Stories
      </h2>
      <p class="text-lg mt-4 text-slate-600 max-w-xl">
        <b>Buttercup Creatives</b> is your go-to partner for professional writing, social media management, proofreading,
        and content editing. We offer comprehensive digital and print solutions to craft your message and grow your presence.
      </p>
      <div class="mt-6 flex flex-col sm:flex-row gap-3">
        <LandingLink
          href="/"
          rel="noopener"
          >Get Started</LandingLink
        >
        <LandingLink
          size="lg"
          styleName="outline"
          rel="noopener"
          href="/about"
          >Learn More</LandingLink
        >
      </div>
    </div>
  </main>
</template>
