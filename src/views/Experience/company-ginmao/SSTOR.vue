<template>
  <ProjectWrap
    class="pl-4"
    :title="t('SSTOR.name')"
    :btn-label="t('stack')"
    :description="t('SSTOR.description')"
  >
    <template #lib>
      <button class="my-btn info">JAVA</button>
      <button class="my-btn info">Spring</button>
      <button class="my-btn info">JSP</button>
      <button class="my-btn info">POI</button>
    </template>
    <ListWrap
      :title="t('contributions')"
      :list="lists"
      inner
      bold
      type="dl"
    />
  </ProjectWrap>
</template>

<script setup lang="ts">
import { computed } from 'vue'
import ProjectWrap from '../../../components/ProjectWrap/ProjectWrap.vue'
import ListWrap from '../../../components/ListWrap/ListWrap.vue'
import { useI18n } from 'vue-i18n'
const { t } = useI18n()

const lists = computed(() => [t('SSTOR.d1'), t('SSTOR.d2'), t('SSTOR.d3')])
</script>
