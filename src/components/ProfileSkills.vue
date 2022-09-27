<template>
    <div class="profile-skills skills">
      <h2 class="skills-title">Skills</h2>
      <skill-list />
    </div>
</template>
<script>
export default {
    name: 'profile-skills'
}
</script>
<style lang="scss">
.profile-skills {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 1rem;
}
.skills-title {
    font-size: 2rem;
    font-weight: 600;
    @media screen and (max-width: 650px) {
    font-size: 1.5rem;
  }
}
</style>