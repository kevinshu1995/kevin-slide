<template>
    <div class="flex gap-4 justify-center">
        <a :href="configs.github" target="_blank" class="hover:!text-emerald-500" style="border: 0">
            <mdi-github />
        </a>
        <a :href="configs.linkedin" target="_blank" class="hover:!text-emerald-500" style="border: 0">
            <ion-logo-linkedin />
        </a>
        <a :href="`mailto:${configs.email}`" target="_blank" class="hover:!text-emerald-500" style="border: 0">
            <mdi-email-fast />
        </a>
    </div>
</template>

<script>
export default {
    props: {
        configs: Object,
    },
};
</script>
