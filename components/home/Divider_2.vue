<template>
  <div class="mx-auto bg-primary">
    <div class="flex items-center justify-between overflow-hidden">
      <div class="w-1/2 hidden md:block text-white">
        <div class="flex flex-col">
          <div class="p-12">
            <h1
              role="heading"
              tabindex="0"
              class="text-3xl font-bold 2xl:leading-10 leading-0"
            >
              TELEASSISTENZA
            </h1>
            <h1 class="py-4">
              Connettersi con l’App ti permetterà di entrare subito in contatto
              con un’agenzia sempre operativa che si occupa di trovare il
              professionista impegnato nel settore sanitario più adatto alle tue
              esigenze.
            </h1>
            <h1
              role="heading"
              tabindex="0"
              class="text-3xl font-bold 2xl:leading-10 leading-0"
            >
              Scegliere Progetto Assistenza vuol dire ottenere soluzioni
              immediate al giusto prezzo.
            </h1>
          </div>
        </div>
      </div>
      <figure class="w-1/2 hidden md:block">
        <img src="/teleassistenza.jpg" />
      </figure>
    </div>
    <div class="block md:hidden text-white">
      <div class="flex flex-col">
        <div class="p-12">
          <h1
            role="heading"
            tabindex="0"
            class="text-3xl font-bold 2xl:leading-10 leading-0"
          >
            TELEASSISTENZA
          </h1>
          <h1 class="py-4">
            Connettersi con l’App ti permetterà di entrare subito in contatto
            con un’agenzia sempre operativa che si occupa di trovare il
            professionista impegnato nel settore sanitario più adatto alle tue
            esigenze.
          </h1>
          <h1
            role="heading"
            tabindex="0"
            class="md:text-3xl text-2xl font-bold 2xl:leading-10 leading-0"
          >
            Scegliere Progetto Assistenza vuol dire ottenere soluzioni immediate
            al giusto prezzo.
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
  "Ausili per anziani e disabili",
];
</script>

<style scoped>
.bullet-list {
  list-style-type: disc;
}
</style>
