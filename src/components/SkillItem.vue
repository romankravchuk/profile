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
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 0.3rem;
    transition: 0.5s ease 0s;

    @media screen and (max-width: 650px) {
        flex: 1 1 40%;
    }
}
</style>