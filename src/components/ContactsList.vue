<template>
    <ul class="contacts-list">
        <contacts-item>
          <a href="https://telegram.me/ak1m1tsu" class="telegram" target="_blank">
            <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-telegram" width="50" height="50" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
              <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
              <path d="M15 10l-4 4l6 6l4 -16l-18 7l4 2l2 6l3 -4"></path>
            </svg>
          </a>
        </contacts-item>
      </ul>
</template>
<script>
export default {
    name: "contacts-list"
}
</script>
<style lang="scss">
.contacts-list {
  padding: 1rem;
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
  gap: 1rem;
  @media screen and (max-width: 768px) {
   flex-direction: column;
  }
} 
</style>