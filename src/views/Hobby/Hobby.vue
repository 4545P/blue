<template>
  <Section
    :title="t('hobbies')"
    icon="xingquaihao">
    <div class="flex flex-wrap justify-start *:overflow-hidden *:relative *:ring-1 *:ring-[var(--border)] dark:*:ring-[var(--focus-border)] *:rounded *:flex *:items-center *:justify-center *:size-12 *:mr-3 *:mb-3 *:dark:hover:text-white">
      <Steam />
      <Book />
      <Music />
      <Movie />
      <Singer />
    </div>
  </Section>
</template>

<script setup lang="ts">
import Section from '../../components/Layouts/Section.vue'
import Music from './4music.vue'
import Movie from './5movie.vue'
import Singer from './6singer.vue'
import Steam from './7steam.vue'
import Book from './8book.vue'
import { useI18n } from 'vue-i18n'
const { t } = useI18n()
</script>
