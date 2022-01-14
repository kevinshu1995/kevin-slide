<template>
    <a :href="href" target="_blank">
        <slot>
            {{ text }}
        </slot>
        <ic-round-keyboard-double-arrow-right />
    </a>
</template>

<script>
export default {
    props: {
        href: String,
        text: String,
    },
};
</script>
