<template>
    <div class="mx-auto bg-[#144e99]">
        <div class="flex items-center justify-between w-full overflow-hidden">
            <figure class="w-1/2 hidden md:block">
                <div>
                    <img class="object-none" src="/home_assistenza.jpg" />
                </div>
            </figure>
            <div class="w-1/2 hidden md:block">
                <div class="flex flex-col text-white">
                    <div class="px-12">
                        <h1
                        role="heading"
                        tabindex="0"
                        class="text-3xl font-bold 2xl:leading-10 leading-0"
                        >
                        I NOSTRI SERVIZI
                        </h1>
                        <ul class="py-4 ml-5">
                            <li v-for="(servicio, index) in servicios" :key="index" class="bullet-list">{{ servicio }}</li>
                        </ul>
                        <h1
                        role="heading"
                        tabindex="0"
                        class="text-3xl font-bold 2xl:leading-10 leading-0"
                        >
                        Scegliere Progetto Assistenza vuol dire ottenere soluzioni immediate al giusto prezzo.
                        </h1>
                    </div>
                </div>
            </div>
        </div>
        <div class="block md:hidden m-auto">
            <div class="flex flex-col text-white">
                    <div class="w-full p-12">
                        <h1
                        role="heading"
                        tabindex="0"
                        class="text-3xl font-bold 2xl:leading-10 leading-0"
                        >
                        I NOSTRI SERVIZI
                        </h1>
                        <ul class="py-4 ml-5">
                            <li v-for="(servicio, index) in servicios" :key="index" class="bullet-list">{{ servicio }}</li>
                        </ul>
                        <h1
                        role="heading"
                        tabindex="0"
                        class="md:text-3xl text-2xl font-bold 2xl:leading-10 leading-0"
                        >
                        Scegliere Progetto Assistenza vuol dire ottenere soluzioni immediate al giusto prezzo.
                        </h1>
                    </div>
                </div>
        </div>
    </div>
</template>

<script setup>
const servicios = [
  "Assistenza alla persona ospedaliera o domiciliare, diurna o notturna",
  "Telemedicina, holter cardiaci, holter pressori a domicilio",
  "Assistenza semplice, qualificata, infermieristica o fisioterapica",
  "Inserimento, integrazione e sostituzione badante",
  "Ausili per anziani e disabili"
];
</script>

<style scoped>
.bullet-list {
  list-style-type: disc;
}</style>