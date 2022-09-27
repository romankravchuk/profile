<template>
    <ul class="skills-list">
        <SkillItem class="django">
          <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-django" width="50" height="50" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
            <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
            <rect x="3" y="3" width="18" height="18" rx="3"></rect>
            <path d="M12 7v8.5l-2.015 .201a2.715 2.715 0 1 1 0 -5.402l2.015 .201"></path>
            <path d="M16 7v.01"></path>
            <path d="M16 10v5.586c0 .905 -.36 1.774 -1 2.414"></path>
          </svg>
        </SkillItem>
        <SkillItem class="html">
          <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-html5" width="50" height="50" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
            <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
            <path d="M20 4l-2 14.5l-6 2l-6 -2l-2 -14.5z"></path>
            <path d="M15.5 8h-7l.5 4h6l-.5 3.5l-2.5 .75l-2.5 -.75l-.1 -.5"></path>
          </svg>
        </SkillItem>
        <SkillItem class="css">
          <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-css3" width="50" height="50" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
            <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
            <path d="M20 4l-2 14.5l-6 2l-6 -2l-2 -14.5z"></path>
            <path d="M8.5 8h7l-4.5 4h4l-.5 3.5l-2.5 .75l-2.5 -.75l-.1 -.5"></path>
          </svg>
        </SkillItem>
        <SkillItem class="javascript">
          <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-javascript" width="50" height="50" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
            <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
            <path d="M20 4l-2 14.5l-6 2l-6 -2l-2 -14.5z"></path>
            <path d="M7.5 8h3v8l-2 -1"></path>
            <path d="M16.5 8h-2.5a0.5 .5 0 0 0 -.5 .5v3a0.5 .5 0 0 0 .5 .5h1.423a0.5 .5 0 0 1 .495 .57l-.418 2.93l-2 .5"></path>
          </svg>
        </SkillItem>
        <SkillItem class="vue">
          <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-vue" width="50" height="50" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
            <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
            <path d="M16.5 4l-4.5 8l-4.5 -8"></path>
            <path d="M3 4l9 16l9 -16"></path>
          </svg>
        </SkillItem>
        <SkillItem class="sass">
          <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-sass" width="50" height="50" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
            <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
            <circle cx="12" cy="12" r="9"></circle>
            <path d="M12 10.523c2.46 -.826 4.002 -.826 4.002 -2.155c0 -1.366 -1.347 -1.366 -2.735 -1.366c-1.91 0 -3.352 .49 -4.537 1.748c-.848 .902 -1.027 2.449 -.153 3.307c.973 .956 3.206 1.789 2.884 3.493c-.233 1.235 -1.469 1.823 -2.617 1.202c-.782 -.424 -.454 -1.746 .626 -2.512s2.822 -.992 4.1 -.24c.98 .575 1.046 1.724 .434 2.193"></path>
          </svg>
        </SkillItem>
    </ul>
</template>
<script>
import SkillItem from './SkillItem.vue';

export default {
    name: "skill-list",
    components: { SkillItem }
}
</script>
<style lang="scss">
.skills-list {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 1rem;
}
.github {
  color: #161b22;
  &:hover {
    color: #000000;
  }
}
.telegram {
  color: #29a9eb;
  &:hover {
    color: #2084b7;
  }
}
.gmail {
  &:hover {
    opacity: 0.7;
  }
}
.django { 
  color: #0c4b33;
  &:hover {
    color: #03180e;
  }
}
.sass {
  color: #c66394;
  &:hover {
    color: #93496d;
  }
}
.html {
  color: #dd4b25;
  &:hover {
    color: #aa391c;
  }
}
.css {
  color: #264de4;
  &:hover {
    color: #1d3bb1;
  }
}
.javascript {
  color: #efd81d;
  &:hover {
    color: #bca916;
  }
}
.vue {
  color: #41bb85;
  &:hover {
    color: #2f8760;
  }
}
</style>