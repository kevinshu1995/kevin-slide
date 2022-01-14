<template>
    <h1 class="flex items-start gap-2">
        <span>
            {{ title }}
        </span>
        <Badge theme="text-white bg-emerald-500" size="xs">
            {{ badge }}
        </Badge>
    </h1>
</template>

<script>
export default {
    props: {
        title: String,
        badge: String,
    },
};
</script>
