<template>
    <figure class="avatar-img">
      <img src="../assets/avatar.jpg" alt="...">
    </figure>
</template>
<script>
export default {
    name: "profile-avatar"
}
</script>
<style lang="scss">
.avatar-img img {
    margin: auto;
    width: 200px;
    border-radius: 50%;
    object-fit: cover;
    display: block;
    box-shadow: 0 10px 60px -10px rgba(13, 28, 39, .5);
    @media screen and (max-width: 650px) {
        width: 100px;
    }
}
</style>