<template>
  <div>
    <div>
      <div
        class="hero min-h-screen"
        style="background-image: url(slider_3.jpg)"
      >
        <div class="hero-overlay bg-opacity-60"></div>
        <div class="hero-content text-center text-neutral-content">
          <div class="max-w-2xl">
            <h1 class="mb-5 text-5xl font-bold">CI PRENDIAMO CURA DI TE</h1>
            <p class="mb-5">
              A cuore il benessere fisico ed emotivo dei nostri assistiti
            </p>
          </div>
        </div>
      </div>
    </div>
    <GeneralTextSection />
    <HomeDivider />
    <div class="py-16 flex flex-col items-center justify-center bg-base-100">
      <div class="w-full xl:px-48 m:px-20 px-8">
        <h1
          role="heading"
          tabindex="0"
          class="text-4xl font-bold 2xl:leading-10 leading-0 text-center text-primary"
        >
          UN SERVIZIO SU MISURA PER TE
        </h1>
        <h2
          role="contentinfo"
          tabindex="0"
          class="text-base leading-normal text-center text-gray-600 mt-5"
        >
          Ogni assistito necessita di un programma specifico che possa giovarlo
          sia da un punto di vista pratico che emotivo. <br />
          Il programma prevede una prima fase di attenta valutazione, per
          identificare le necessità del assistito cosi che si formuli,
          coordinando con il responsabile (caregiver), un servizio mirato.
          Grazie alle diverse risorse a supporto (insieme di badanti, oss ed
          infermieri) ci permette di poter sodisfare quest’aspettativa.
        </h2>
      </div>
    </div>
    <HomeDivider2 />
    <HomeTextImage />
    <GeneralAddress />
    <GeneralOurPartners />
  </div>
</template>

<script setup lang="ts">
definePageMeta({
  layout: "default",
});
</script>
