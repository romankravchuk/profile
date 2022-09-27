<template lang="">
    <div class="profile-contacts">
      <h2 class="contacts-title">Contacts</h2>
      <contacts-list />
    </div>
</template>
<script>
export default {
    name: "profile-contacts"
}
</script>
<style lang="scss">
.profile-contacts {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 1rem;
}
.contacts-title {
  font-size: 2rem;
  font-weight: 600;
  @media screen and (max-width: 650px) {
    font-size: 1.5rem;
  }
}
</style>