<template>
    <div class="profile-description">
      <h1>Roman Kravchuk</h1>
      <div>Back-end Developer</div>
      <div class="profile-location">
        <a href="https://www.google.com/maps/place/Irkutsk,+Irkutsk+Oblast/@52.2982526,104.1270757,11z/data=!3m1!4b1!4m5!3m4!1s0x5da83ad353e2f665:0x31d6cd1456d8e94e!8m2!3d52.2854834!4d104.2890222" target="_blank">
          <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-map-pin" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
            <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
            <circle cx="12" cy="11" r="3"></circle>
            <path d="M17.657 16.657l-4.243 4.243a2 2 0 0 1 -2.827 0l-4.244 -4.243a8 8 0 1 1 11.314 0z"></path>
          </svg>
          <span>Russia, Irkutsk</span>
        </a>
      </div>
    </div>
</template>
<script>
export default {
    name: "profile-description"
}
</script>
<style lang="scss">
.profile-description {
    text-align: center;
    display: flex;
    flex-direction: column;
    gap: 0.6rem;

    h1 {
        font-size: 2.2rem;
        font-weight: bold;

        & + div {
        font-size: 1.3rem;
        }
    }
}
.profile-location {
    display: inline-flex;
    margin: 0.3rem 0;
    justify-content: center;
    a {
        display: flex;
        align-items: center;
        gap: 0.5rem;
        &:hover {
        text-decoration: underline;
        }
    }
}
</style>