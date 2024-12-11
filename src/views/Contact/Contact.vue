<template>
  <Section
    :title="t('contact.title')"
    icon="lianxi">
    <RowContent
      :label="t('contact.r1')"
      text="0979201282" />
    <RowContent
      :label="t('contact.r2')"
      text="prosr123692010@gmail.com" />
    <RowContent
      link
      :label="t('contact.r3')"
      text="https://github.com/4545P" />
  </Section>
</template>

<script setup lang="ts">
import Section from '../../components/Layouts/Section.vue'
import RowContent from '../../components/RowContent/RowContent.vue'
import { useI18n } from 'vue-i18n'
const { t } = useI18n()
</script>
