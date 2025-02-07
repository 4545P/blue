<template>
  <div class="grid grid-cols-1 gap-3 sm:grid-cols-2 md:grid-cols-2 lg:grid-cols-3">
    <RepositoryItem
      :name="t('personal.r1')"
      :description="t('personal.r1')"
      link="https://github.com/4545P/book_borrowing"
      class="h-[110px]">
      <div class="flex flex-row">
        <div class="flex-1">
          {{ t('personal.recommend') }}
          <div>{{ t('personal.r1_t1') }}</div>
          <div>{{ t('personal.r1_t2') }}</div>
        </div>
        <a
          class="flex items-center justify-center p-4 cursor-pointer"
          href="https://github.com/4545P/book_borrowing"
          target="_blank">
          <Iconfont
            name="tiaozhuan"
            :size="22" />
        </a>
      </div>
    </RepositoryItem>

    <RepositoryItem
      :name="t('personal.r2')"
      transitionType="fromLeft"
      :description="t('personal.r2')"
      link="https://github.com/4545P/book_borrowingWeb"
      class="h-[110px]">
      <div class="flex flex-row">
        <div class="basis-full flex flex-wrap flex-row gap-1">
          <img
            alt="Static Badge"
            src="https://img.shields.io/badge/%E5%89%8D%E7%AB%AF%E6%A1%86%E6%9E%B6-Vue3-%236495ed" />
          <img
            alt="Static Badge"
            src="https://img.shields.io/badge/%E8%84%9A%E6%9C%AC%E8%AA%9E%E8%A8%80-TypeScript-%25236495ed" />
          <img
              alt="Static Badge"
              src="https://img.shields.io/badge/UI-Element Plus-%238a2be2" />
        </div>
        <a
          class="flex items-center justify-center p-4 cursor-pointer"
          href="https://github.com/4545P/book_borrowingWeb"
          target="_blank">
          <Iconfont
            name="tiaozhuan"
            :size="22" />
        </a>
      </div>
    </RepositoryItem>

    <RepositoryItem
      :name="t('personal.r3')"
      :description="t('personal.r3')"
      transitionType="fromTop"
      link="https://github.com/4545P/course_management"
      class="h-[110px]">
      <div class="flex flex-row">
        <div class="flex-1">
          {{ t('personal.recommend') }}
          <div>{{ t('personal.r3_t1') }}</div>
          <div>{{ t('personal.r3_t2') }}</div>
        </div>
        <a
          class="flex items-center justify-center p-4 cursor-pointer"
          href="https://github.com/4545P/course_management"
          target="_blank">
          <Iconfont
            name="tiaozhuan"
            :size="22" />
        </a>
      </div>
    </RepositoryItem>

    <RepositoryItem
      :name="t('personal.r4')"
      :description="t('personal.r4')"
      transitionType="fromRight"
      link="https://github.com/4545P/course_managementWeb"
      class="h-[110px]">
      <div class="flex flex-row">
        <div class="basis-full flex flex-wrap flex-row gap-1">
          <img
              alt="Static Badge"
              src="https://img.shields.io/badge/%E5%89%8D%E7%AB%AF%E6%A1%86%E6%9E%B6-Vue3-%236495ed" />
          <img
              alt="Static Badge"
              src="https://img.shields.io/badge/%E8%84%9A%E6%9C%AC%E8%AA%9E%E8%A8%80-TypeScript-%25236495ed" />
          <img
              alt="Static Badge"
              src="https://img.shields.io/badge/UI-Element Plus-%238a2be2" />
        </div>
        <a
          class="flex items-center justify-center p-4 cursor-pointer"
          href="https://github.com/4545P/course_managementWeb"
          target="_blank">
          <Iconfont
            name="tiaozhuan"
            :size="22" />
        </a>
      </div>
    </RepositoryItem>

    <RepositoryItem
        :name="t('personal.r5')"
        :description="t('personal.r5')"
        link="https://github.com/4545P/questionnaire"
        class="h-[110px]">
      <div class="flex flex-row">
        <div class="flex-1">
          {{ t('personal.recommend') }}
          <div>{{ t('personal.r5_t1') }}</div>
          <div>{{ t('personal.r5_t2') }}</div>
        </div>
        <a
            class="flex items-center justify-center p-4 cursor-pointer"
            href="https://github.com/4545P/questionnaire"
            target="_blank">
          <Iconfont
              name="tiaozhuan"
              :size="22" />
        </a>
      </div>
    </RepositoryItem>

    <RepositoryItem
        :name="t('personal.r6')"
        :description="t('personal.r6')"
        transitionType="fromLeft"
        link="https://github.com/4545P/questionnaireWeb"
        class="h-[110px]">
      <div class="flex flex-row">
        <div class="basis-full flex flex-wrap flex-row gap-1">
          <img
              alt="Static Badge"
              src="https://img.shields.io/badge/%E5%89%8D%E7%AB%AF%E6%A1%86%E6%9E%B6-Vue2-%236495ed" />
          <img
              alt="Static Badge"
              src="https://img.shields.io/badge/%E8%84%9A%E6%9C%AC%E8%AA%9E%E8%A8%80-TypeScript-%25236495ed" />
          <img
              alt="Static Badge"
              src="https://img.shields.io/badge/UI-Element Plus-%238a2be2" />
        </div>
        <a
            class="flex items-center justify-center p-4 cursor-pointer"
            href="https://github.com/4545P/questionnaireWeb"
            target="_blank">
          <Iconfont
              name="tiaozhuan"
              :size="22" />
        </a>
      </div>
    </RepositoryItem>

    <RepositoryItem
        :name="t('personal.r7')"
        :description="t('personal.r7')"
        transitionType="fromTop"
        link="https://github.com/4545P/qulingyu"
        class="h-[110px]">
      <div class="flex flex-row">
        <div class="basis-full flex flex-wrap flex-row gap-1 ">
          <img
              alt="Static Badge"
              src="https://img.shields.io/badge/%E8%84%9A%E6%9C%AC%E8%AA%9E%E8%A8%80-python-%25236495ed" />
          <div class="invisible">
            <img alt="Invisible Placeholder" src="https://via.placeholder.com/150" />
          </div>
          <div class="invisible">
            <img alt="Invisible Placeholder" src="https://via.placeholder.com/150" />
          </div>
        </div>
        <a
            class="flex items-center justify-center p-4 cursor-pointer"
            href="https://github.com/4545P/blue?tab=readme-ov-file"
            target="_blank">
          <Iconfont
              name="tiaozhuan"
              :size="22" />
        </a>
      </div>
    </RepositoryItem>

    <!-- 项目虽好，但求面试还写刷面试的，场景过于不适 -->
    <!-- 听取老师建议，PDF把这个效果去掉了 -->
    <!-- 在线简历方便演示估计也没人注意细节暂且保留 -->
<!--    <RepositoryItem-->
<!--      name="FE-prepare-interview"-->
<!--      transitionType="fadeIn"-->
<!--      :description="t('personal.r5')"-->
<!--      link="https://github.com/Fridolph/FE-prepare-interview">-->
<!--      <div class="flex flex-row">-->
<!--        <div class="flex flex-wrap gap-y-2">-->
<!--          <button class="my-btn">{{ t('personal.b1') }}</button>-->
<!--          <button class="my-btn">Promise</button>-->
<!--          <button class="my-btn">{{ t('personal.b3') }}</button>-->
<!--          <button class="my-btn">http</button>-->
<!--          <button class="my-btn">{{ t('personal.b5') }}</button>-->
<!--          <button class="my-btn">{{ t('personal.b6') }}</button>-->
<!--        </div>-->
<!--        <a-->
<!--          class="flex items-center justify-center p-4 cursor-pointer"-->
<!--          href="https://github.com/Fridolph/FE-prepare-interview"-->
<!--          target="_blank">-->
<!--          <Iconfont-->
<!--            name="tiaozhuan"-->
<!--            :size="22" />-->
<!--        </a>-->
<!--      </div>-->
<!--    </RepositoryItem>-->
  </div>
</template>

<script setup lang="ts">
import RepositoryItem from '../../components/RepositoryItem/RepositoryItem.vue'
import Iconfont from '../../components/Iconfont/Iconfont.vue'
import { useI18n } from 'vue-i18n'
const { t } = useI18n()
</script>

<style scoped>
.invisible {
  visibility: hidden;
}
</style>
