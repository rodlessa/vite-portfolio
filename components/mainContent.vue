<template>
    <div class="max-w-3xl mx-auto px-4 sm:px-6 xl:max-w-5xl xl:px-0 mt-10 space-y-4 ">
        <p class="text-sky-500	">Olá eu sou,</p>
<h1 class="text-sky-500 text-3xl leading-9 font-extrabold tracking-tight sm:text-4xl sm:leading-10 md:text-6xl md:leading-14 px-4">Rodrigo Lessa</h1>
<Typed :options="options">
    <h3 class="typing yping text-sky-500 text-4xl"></h3>
  </Typed>
<p class="nota  m-0">Desenvolvo aplicações voltadas para web, especilazado em cloud e computação distribuida. Foco em DevOps e processos de doployment para aplicações com voltadas a eslasticidade.</p>


</div>
</template>
<script setup lang="ts">
import { Typed } from "@duskmoon/vue3-typed-js";
import type { TypedOptions } from "@duskmoon/vue3-typed-js";

const options: TypedOptions = {
  cursor: false,
  strings: ["Analista de Sistemas", "AWS - Architect Solutions", "Backend developer", "Front-end Developer"],
  loop: true,
  typeSpeed: 50,
  showCursor: false,
  backSpeed: 60,

};
</script>