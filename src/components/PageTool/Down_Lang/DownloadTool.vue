<template>
  <div class="flex item-center justify-center hover:text-sky-400 dark-transition">
    <Iconfont
      :size="22"
      name="xiazai"
      @click="downloadPdf" /> 
  </div>
</template>

<script setup lang="ts">
import Iconfont from '../../Iconfont/Iconfont.vue'
function downloadPdf() {
  let $el = document.createElement('a')
  $el.href = 'https://blue4545.netlify.app/java_laijiteng_2y.pdf'
  $el.target = '_blank'
  $el.download = `賴紀滕-經驗2年-JAVA後端.pdf`
  document.body.appendChild($el)
  $el.click()
  document.body.removeChild($el)
}
</script>
