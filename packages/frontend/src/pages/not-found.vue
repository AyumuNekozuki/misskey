<template>
<div class="ipledcug">
	<div class="_fullinfo">
		<img src="https://misskey-white.s3.ap-northeast-1.amazonaws.com/mashiro/mashiro_bg_c_256.png" class="_ghost"/>
		<div>{{ i18n.ts.notFoundDescription }}</div>
	</div>
</div>
</template>

<script lang="ts" setup>
import { i18n } from '@/i18n';
import { definePageMetadata } from '@/scripts/page-metadata';

const headerActions = $computed(() => []);

const headerTabs = $computed(() => []);

definePageMetadata({
	title: i18n.ts.notFound,
	icon: 'ti ti-alert-triangle',
});
</script>
