<template>
  <div class="flex items-center p-2 rounded-xl border-2 bg-gray-50">
    <img
      :src="imageSrc"
      class="w-[120px] h-[120px] rounded-2xl"
      :alt="`${name}のプロフィール`"
    />
    <div class="ml-6">
      <div class="text-[30px] font-semibold">
        {{ name }}（{{ nickname }}）
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MemberCard',
  props: {
    name: {
      type: String,
      required: true
    },
    nickname: {
      type: String,
      required: true
    },
    imageSrc: {
      type: String,
      required: true
    }
  }
};
</script>

