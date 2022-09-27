<template>
    <div class="profile-card">
    <profile-avatar />
    <profile-description />
    <profile-skills />
    <profile-contacts />
    <profile-actions />
  </div>
</template>
<script>
export default {
    name: "profile"
}
</script>
<style lang="scss">
.profile-card {
  box-shadow: 0 10px 200px -60px black;
  border-radius: 50px;
  width: 700px;
  position: relative;
  backdrop-filter: blur(15px);
  border: 2px solid #ffffff40;
  padding: 3rem 5rem;
  display: flex;
  flex-direction: column;
  gap: 2rem;

  @media screen and (max-width: 768px) {
    width: auto;
  }
}    
</style>