<template>
  <ProjectWrap
    class="pl-4"
    :title="t('WebMoiKcg.name')"
    :btn-label="t('stack')"
    :description="t('WebMoiKcg.description')"
  >
    <template #lib>
      <button class="my-btn info">JAVA</button>
      <button class="my-btn info">JSP</button>
      <button class="my-btn info">POI</button>
    </template>
    <ListWrap
      :title="t('contributions')"
      :list="saasList"
      inner
      bold
      type="ul"
    />

    <!-- <ListWrap
      :title="t('hard')"
      :list="hardList"
      inner
      bold /> -->
  </ProjectWrap>
</template>

<script setup lang="ts">
import { computed } from 'vue'
import ProjectWrap from '../../../components/ProjectWrap/ProjectWrap.vue'
import ListWrap from '../../../components/ListWrap/ListWrap.vue'
import { useI18n } from 'vue-i18n'
const { t } = useI18n()

const saasList = computed(() => [
  t('WebMoiKcg.d1'),
  t('WebMoiKcg.d2'),
  t('WebMoiKcg.d3'),
  t('WebMoiKcg.d4'),
  t('WebMoiKcg.d5'),
])
</script>
