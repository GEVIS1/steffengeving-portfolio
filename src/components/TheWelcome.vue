<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
import lorem from 'vue-lorem-ipsum'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading><lorem add="1w"></lorem></template>

    <lorem add="1s"></lorem>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading><lorem add="1w"></lorem></template>

    <lorem add="1s"></lorem>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading><lorem add="1w"></lorem></template>

    <lorem add="1s"></lorem>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading><lorem add="1w"></lorem></template>

    <lorem add="1s"></lorem>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading><lorem add="1w"></lorem></template>

    <lorem add="1s"></lorem>
  </WelcomeItem>
</template>
