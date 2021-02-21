<template>
  <div class="border-2 border-black items-center rounded-xl flex flex-col w-64 py-5 px-3 space-y-8 text-black cursor-pointer font-extralight shadow-2xl" 
  :class="[value.color, value.texthover]">
    <img :src="value.image" class="w-20 h-20"/>
    <span class="uppercase text-2xl font-bold">{{value.name}}</span>
    <span>{{value.description}}</span>
    <a :href="value.link" target="_balnk" class="border border-black bg-black text-white rounded-full py-2 px-10 transition duration-500 ease-in-out transform hover:-translate-y-1 hover:scale-110">{{value.boton}}</a>
  </div>
</template>

<script>
export default {
  props: ["value"]
};
</script>