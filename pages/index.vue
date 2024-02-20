<template>
    <div>
        <div>
            <div class="hero min-h-screen" style="background-image: url(slider_3.jpg);">
                <div class="hero-overlay bg-opacity-60"></div>
                <div class="hero-content text-center text-neutral-content">
                    <div class="max-w-md">
                    <h1 class="mb-5 text-5xl font-bold">Hello there</h1>
                    <p class="mb-5">Provident cupiditate voluptatem et in. Quaerat fugiat ut assumenda excepturi exercitationem quasi. In deleniti eaque aut repudiandae et a id nisi.</p>
                    <button class="btn btn-primary">Get Started</button>
                    </div>
                </div>
            </div>
        </div>
        <GeneralTextSection/>
        <HomeDivider/>
        <div class="py-16 flex flex-col items-center justify-center bg-white">
            <div class="w-full xl:px-48 m:px-20 px-8">
                <h1
                role="heading"
                tabindex="0"
                class="text-4xl font-bold 2xl:leading-10 leading-0 text-center text-[#144e99]"
                >
                L’evoluzione dell’assistenza domiciliare
                </h1>
                <h2
                role="contentinfo"
                tabindex="0"
                class="text-base leading-normal text-center text-gray-600 mt-5"
                >
                Scopri l’app da installare su smartphone o Tablet. L’applicazione sarà utilizzabile per le prenotazioni dei servizi di assistenza domiciliare, ospedaliera e dei servizi di telemedicina, sia per il monitoraggio dei parametri vitali che per prestazioni di diagnostica specialistica. Il tutto in costante collegamento con la centrale di ascolto, gestita dal Centro locale, coadiuvato da medici specialisti che prenderanno in carico le refertazioni digitali degli esami eseguiti.
                </h2>
            </div>
        </div>
        <HomeDivider2/>
        <HomeTextImage/>
        <GeneralAddress/>
        <GeneralOurPartners/> 
    </div>
</template>

<script setup lang="ts">
definePageMeta({
  layout: 'default'
})
</script>