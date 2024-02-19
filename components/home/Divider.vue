<template>
    <div class="flex flex-row overflow-hidden">
        <figure class="w-1/2 hidden md:block">
            <img src="https://daisyui.com/images/stock/photo-1606107557195-0e29a4b5b4aa.jpg" alt="Shoes" />
        </figure>
        <div class="w-1/2 pt-4 hidden md:block">
            <div class="flex flex-col">
                <div class="w-full xl:pl-20 xl:pr-12 pl-12 pr-12">
                    <h1
                    role="heading"
                    tabindex="0"
                    class="text-3xl font-bold 2xl:leading-10 leading-0 -ml-5 text-gray-800"
                    >
                    I NOSTRI SERVIZI
                    </h1>
                    <ul class="py-4">
                        <li v-for="(servicio, index) in servicios" :key="index" class="bullet-list">{{ servicio }}</li>
                    </ul>
                    <h1
                    role="heading"
                    tabindex="0"
                    class="text-3xl font-bold 2xl:leading-10 leading-0 -ml-5 text-gray-800"
                    >
                    Scegliere Progetto Assistenza vuol dire ottenere soluzioni immediate al giusto prezzo.
                    </h1>
                </div>
            </div>
        </div>
    </div>
    <div class="block md:hidden">
        <div class="flex flex-col -mr-5">
                <div class="w-full pl-12 pr-12">
                    <h1
                    role="heading"
                    tabindex="0"
                    class="text-3xl font-bold 2xl:leading-10 leading-0 -ml-5 text-gray-800"
                    >
                    I NOSTRI SERVIZI
                    </h1>
                    <ul class="py-4">
                        <li v-for="(servicio, index) in servicios" :key="index" class="bullet-list">{{ servicio }}</li>
                    </ul>
                    <h1
                    role="heading"
                    tabindex="0"
                    class="text-3xl font-bold 2xl:leading-10 leading-0 -ml-5 text-gray-800"
                    >
                    Scegliere Progetto Assistenza vuol dire ottenere soluzioni immediate al giusto prezzo.
                    </h1>
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