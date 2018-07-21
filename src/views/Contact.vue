<template>
    <LinkBar></LinkBar>
</template>


<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import LinkBar from '@/components/LinkBar.vue'; // @ is an alias to /src

@Component({
  components: {
    LinkBar,
  },
})
export default class Contact extends Vue {}
</script>