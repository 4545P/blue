<template>
  <Section
    anchor="Experience"
    :title="t('work')"
    icon="gongzuoxinxi"
  >
    <CompanyGinmao />
    <div class="divide flex my-3"></div>
    <CompanyCourse />
  </Section>
</template>

<script setup lang="ts">
import Section from '../../components/Layouts/Section.vue'
import CompanyGinmao from './company-ginmao/index.vue'
import CompanyCourse from './company-course/index.vue'
import { useI18n } from 'vue-i18n'
const { t } = useI18n()
</script>
