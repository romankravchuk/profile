<template>
    <div class="profile-actions">
      <a href="https://github.com/romankravchuk" target="_blank">Source</a>
    </div>
</template>
<script>
export default {
    name: 'profile-actions'
}
</script>
<style lang="scss">
.profile-actions {
    display: flex;
    justify-content: center;
    align-items: center;
    a {
        font-size: 1.5rem;
        &:hover {
        text-decoration: underline;
        }
    }
}
</style>