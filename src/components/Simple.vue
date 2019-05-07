<template>
  <h1>No script tag in this component</h1>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class Simple extends Vue {
  @Prop() private msg!: string;
}
</script>
