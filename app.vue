<template>
  Dynamic Import
  <!-- Not working -->
  <br />
  <component :is="GroupTest" />
  <br />
  Manual Import
  <br />
  <!-- Working -->
  <grouptest />
  <br />
  Nuxt Import
  <br />
  <GroupTest />
</template>

<script>
import grouptest from '@/components/group/test';

export default {
  components: {
    grouptest,
  },
};
</script>
