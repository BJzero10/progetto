<template>
    <GeneralBanner/>
    <ServiziTextSectionSlot>
        <template v-slot:sectionTitle>
            Assistenza alla persona: professionisti socio sanitari a domicilio e molto di più.
        </template>
        <template v-slot:sectionContent>
            Progetto Assistenza eroga ogni servizio sia a livello domiciliare che presso strutture ospedaliere, di degenza, ricovero o convalescenza, fornendo sostegno continuo 24 ore su 24 – 7 giorni su 7.
            <br/>
            Forte dell’esperienza maturata, Progetto Assistenza seleziona i propri collaboratori in base a esigenti parametri che esaltino determinate caratteristiche di serietà e sensibilità nel rapporto con l’assistito.
            <br/>
            <br/>
            La nostra esperienza più che ventennale, l’etica, il metodo e l’innovazione sono i principi che guidano il nostro lavoro, svolto con professionalità e dedizione.
Scegliere Progetto Assistenza vuol dire ottenere risposte immediate, personale altamente qualificato e soluzioni ad hoc al giusto prezzo.
        </template>
    </ServiziTextSectionSlot>
    <ServiziImgSection/>
    <ServiziAssisHighlights/>
    <ServiziServiceList/>
    <ServiziBanner/>
</template>

<script setup lang="ts">
definePageMeta({
  layout: 'default'
})
</script>