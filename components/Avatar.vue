<template>
    <div :class="['rounded-full overflow-hidden', size]">
        <img class="w-full block" :src="src" alt="avatar" />
    </div>
</template>

<script>
export default {
    props: {
        src: String,
        size: {
            type: String,
            default: "w-150px h-150px",
        },
    },
};
</script>
