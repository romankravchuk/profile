<template>
    <li class="contacts-item">
        <slot></slot>
    </li>
</template>
<script>
export default {
    name: "contacts-item"
}
</script>
<style lang="scss">
.contacts-item a {
    padding: 0.3rem;
    transition: 0.5s ease 0s;
}  
</style>