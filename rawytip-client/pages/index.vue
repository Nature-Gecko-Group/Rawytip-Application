<template>
  <div class="bg-black w-full h-screen flex items-center justify-center">
    <div class="bg-white p-4 w-1/3">
      <div class="text-red-900 font-kanit text-xl font-extralight">
        โดยที่ประชาชนแห่งสหประชาชาติได้ยืนยันอีกครั้งไว้ในกฎบัตรถึงศรัทธาในสิทธิมนุษยชนขั้นพื้นฐาน
      </div>
      <div class="text-red-900 font-kanit text-xl">
        โดยที่ประชาชนแห่งสหประชาชาติได้ยืนยันอีกครั้งไว้ในกฎบัตรถึงศรัทธาในสิทธิมนุษยชนขั้นพื้นฐาน
      </div>
      <div>
        {{ t('test') }}
      </div>
    </div>
    <div class="bg-gray-200">
        {{ locale }}
    </div>


  </div>
</template>


<script setup lang="ts">
const { t, locale } = useI18n()
</script>