<template>
  <div class="text-center box-border mt-16">
    <span class="block text-5xl box-border px-5">Write And See</span>
    <div class="flex justify-center ">
      <input
        v-model="text"
        class="w-full mx-10 border border-slate-300 rounded-md box-border p-4 mt-12 outline-none sm:text-sm"
        placeholder="write something..."
        type="text"
      />
    </div>
  </div>
  <div class="mt-12 text-center text-3xl leading-loose">
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-abril-fatface">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Abril Fatface)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-anybody">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Anybody)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-astloch">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Astloch)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-aubrey">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Aubrey)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-bebas-neue">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Bebas Neue)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-big-shoulders-inline-text">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Big Shoulders Inline Text)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-butcherman">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Butcherman)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-comfortaa">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Comfortaa)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-fasthand">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Fasthand)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-federant">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Federant)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-fredoka-one">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Fredoka One)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-fruktur">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Fruktur)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-geostar">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Geostar)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-geostar-fill">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Geostar Fill)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-hanalei">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Hanalei)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-kenia">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Kenia)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-langar">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Langar)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-lobster">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Lobster)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-miltonian">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Miltonian)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-miltonian-tattoo">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Miltonian Tattoo)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-moulpali">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Moulpali)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-nova-cut">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Nova Cut)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-nova-oval">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Nova Oval)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-nova-script">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Nova Script)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-oi">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Oi)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-passero-one">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Passero One)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-purple-purse">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Purple Purse)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-rubik-bubbles">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Rubik Bubbles)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-rubik-glitch">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Rubik Glitch)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-rubik-microbe">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Rubik Microbe)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-rubik-moonrocks">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Rubik Moonrocks)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-rubik-puddles">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Rubik Puddles)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-rubik-wet-paint">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Rubik Wet Paint)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-sevillana">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Sevillana)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-single-day">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Single Day)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-snowburst-one">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Snowburst One)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-sofadi-one">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Sofadi One)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-stalinist-one">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Stalinist One)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-taprom">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Taprom)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-warnes">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Warnes)</span>
        </div>
      <div v-if="text" class="box-border px-5 overflow-hidden text-ellipsis border-0 border-t-2 py-6 border-solid font-zen-tokyo-zoo">
        <span>{{ text }}</span>
        <br>
        <span class="text-xl font-poppins">(Font Name: Zen Tokyo Zoo)</span>
        </div>
  </div>
</template>

<script>

import { ref } from "vue";

export default {
  setup () {
    const text = ref('text')
    return {
      text
    }
  },
}

</script>