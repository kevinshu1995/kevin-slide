<template>
    <span :class="['rounded', theme, badgeSize]">
        <slot>
            {{ text }}
        </slot>
    </span>
</template>

<script>
export default {
    props: {
        theme: {
            type: String,
            default: "bg-emerald-500",
        },
        size: String,
        text: String,
    },
    computed: {
        badgeSize() {
            switch (this.size) {
                case "xs":
                    return "px-1 py-0 text-xs";
                default:
                    return "px-2 py-1";
            }
        },
    },
};
</script>
