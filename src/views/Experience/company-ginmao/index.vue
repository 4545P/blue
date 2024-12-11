<template>
  <RowContent
    align="right"
    :label="t('ginmao.name')"
    :label-bold="true"
    :label-width="220"
    :is-wrap="true"
    :is-title="true"
    :text="t('ginmao.time')"
  />

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

  <WebMoiKcg />
  <ProXhyx />
</template>

<script setup lang="ts">
import { computed } from 'vue'
import RowContent from '../../../components/RowContent/RowContent.vue'
import ListWrap from '../../../components/ListWrap/ListWrap.vue'
import WebMoiKcg from "@/views/Experience/company-ginmao/WebMoiKcg.vue";
import ProXhyx from './SSTOR.vue'
import { useI18n } from 'vue-i18n'


const { t } = useI18n()

const lists = computed(() => [
  t('ginmao.d1'),
  t('ginmao.d2'),
  t('ginmao.d3'),
  t('ginmao.d4'),
  t('ginmao.d5')])
const results = computed(() => [
  t('ginmao.l1'),
  t('ginmao.l2'),
  t('ginmao.l3'),
  t('ginmao.l4'),
])
</script>
