<template>
    <div class="flex gap-2">
        <Badge v-for="(text, i) in content" size="xs" :key="`badge-${i}-${text}`">
            {{ text }}
        </Badge>
    </div>
</template>

<script>
export default {
    props: {
        content: Array,
    },
};
</script>
