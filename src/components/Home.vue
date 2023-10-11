<script lang="ts" setup>
  // import { viewBindings as ui } from "@vision/nativescript-data";
</script>

<template>
  <Frame>
    <Page>
      <GridLayout>
        <Image src="res://SunSliver" class="align-top w-full" iosOverflowSafeArea="true" stretch="aspectFit" scaleY="1.6" scaleX="1.6" translateY="30" />
        <Image src="res://EarthHalf" class="align-bottom w-full" iosOverflowSafeArea="true" stretch="aspectFill" scaleY="2" scaleX="2" translateY="540" />
      </GridLayout>
    </Page>
  </Frame>
</template>

<style>
  /* .info {
    font-size: 20;
  } */
</style>
