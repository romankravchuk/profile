<template>
    <li class="skills-item">
        <slot></slot>
    </li>
</template>
<script>
export default {
    name: "skill-item"
}
</script>
<style lang="scss">
.skills-item {
    width: 100%;
    padding: 0.3rem;
    transition: 0.5s ease 0s;
}
</style>