<template>
  <RowContent
    align="right"
    :label="t('course.name')"
    :label-bold="true"
    :label-width="220"
    :is-wrap="true"
    :is-title="true"
    :text="t('course.time')" />

  <ListWrap
      :title="t('responsibilities')"
      :list="lists"
      inner
      title-size="base"
      bold
  />

  <ListWrap
      :title="t('ginmao.results')"
      :list="results"
      inner
      title-size="base"
      bold
  />

  <ProXhyx />
</template>

<script setup lang="ts">
import { computed } from 'vue'
import RowContent from '../../../components/RowContent/RowContent.vue'
import ListWrap from '../../../components/ListWrap/ListWrap.vue'
import ProXhyx from './ProXhyx.vue'
import { useI18n } from 'vue-i18n'
const { t } = useI18n()

const lists = computed(() => [
  t('course.r1'),
  t('course.r2'),
  t('course.r3'),
])
const results = computed(() => [
  t('course.l1'),
  t('course.l2'),
  t('course.l3'),
])
</script>
