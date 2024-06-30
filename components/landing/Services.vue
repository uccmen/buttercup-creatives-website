<script setup>
const services = [
  {
    title: "Custom Content Creation",
    description:
      "Craft tailored content that speaks directly to your audience, from blog posts and articles to social media updates and print materials.",
    icon: "bx:bxs-briefcase",
  },
  {
    title: "Expert Proofreading and Editing",
    description:
      "Ensure your content is polished, professional, and error-free with our meticulous proofreading and editing services for both digital and print.",
    icon: "bx:bxs-window-alt",
  },
  {
    title: "Strategic Social Media Management",
    description:
      "Boost your brand’s visibility and engagement with our strategic social media management solutions.",
    icon: "bx:bxs-data",
  },
  {
    title: "Professional Writing Services",
    description:
      "Tell your story effectively with our professional writing services, including copywriting, ghostwriting, and more.",
    icon: "bx:bxs-pen",
  }
];
</script>

<template>
  <div id="services" class="mt-16 md:mt-0">
    <h2 class="text-4xl lg:text-5xl font-bold lg:tracking-tight">
      Elevate Your Brand with Online and Offline Expertise
    </h2>
    <p class="text-lg mt-4 text-slate-600">
      Buttercup Creatives offers a comprehensive suite of services designed
      to enhance your online and offline presence and connect with your audience effectively.
    </p>
  </div>

  <div class="grid sm:grid-cols-2 md:grid-cols-4 mt-16 gap-16">
    <div v-for="item of services" class="flex gap-4 items-start">
      <div class="mt-1 bg-black rounded-full p-2 w-8 h-8 shrink-0">
        <Icon class="text-white" :name="item.icon" />
      </div>
      <div>
        <h3 class="font-semibold text-lg">{{ item.title }}</h3>
        <p class="text-slate-500 mt-2 leading-relaxed">
          {{ item.description }}
        </p>
      </div>
    </div>
  </div>
</template>
