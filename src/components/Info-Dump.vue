<template>
    <div class="p-6 bg-blue-300 flex">
        <div class="flex-grow-[2]">
            <h2 class="text-2xl font-bold mb-2 text-white font-body">Informații despre New York</h2>
            <p class="mb-4 text-slate-50">New York, cunoscut și sub numele de "Orașul care nu doarme", este cel mai populat oraș din Statele Unite. Este renumit pentru peisajul său urban vast, fiind acasă la numeroase zgârie-nori impresionanți, inclusiv faimosul Empire State Building.</p>
            <p class="mb-4 text-slate-50" >Orașul găzduiește și numeroase parcuri, cum ar fi Central Park, care oferă o oază de liniște în inima orașului aglomerat. De asemenea, New York este un centru cultural și artistic major, cu multe muzee, galerii de artă, și teatre.</p>
            <p class="mb-4 text-slate-50">Pe lângă acestea, New York este cunoscut pentru diversitatea sa culinară, oferind o gamă largă de opțiuni de mâncare din întreaga lume.</p>
        </div>
        <div class="flex flex-col"> 
            <Clock-Widget />
            <span class="text-center italic">Ora in New York</span>
        </div>
    </div>
</template>

<script setup>
import ClockWidget from './Clock-Widget.vue'

</script>
