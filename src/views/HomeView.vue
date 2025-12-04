<template>
  <div>
    <HomeHeader />
    <TaskBoard />
    <ExitModal />
    <NewCardModal />
    <TaskModal />
  </div>
</template>

<script setup>
import ExitModal from "@/components/ExitModal.vue";
import HomeHeader from "@/components/HomeHeader.vue";
import NewCardModal from "@/components/NewCardModal.vue";
import TaskBoard from "@/components/TaskBoard.vue";
import TaskModal from "@/components/TaskModal.vue";
</script>

<style lang="scss" scoped></style>
