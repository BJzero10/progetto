<template>
    <div class="py-10 flex flex-col items-center justify-center bg-white">
      <div class="w-full xl:px-24 m:px-16 px-8">
        <h1 role="heading" tabindex="0" class="text-4xl font-bold 2xl:leading-10 leading-0 text-justify text-[#144e99]">
            <slot name="sectionTitle"></slot>
        </h1>
        <h2 role="contentinfo" tabindex="0" class="text-base leading-normal text-justify text-gray-600 mt-10">
            <slot name="sectionContent"></slot>
        </h2>
      </div>
    </div>
  </template>