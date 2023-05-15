<template>
<nav>
    <NuxtLink to="/about">ABOUT</NuxtLink>
    <NuxtLink to="/socials">SOCIALS</NuxtLink>
    <NuxtLink to="/events">EVENTS</NuxtLink>
    <NuxtLink to="/videos">VIDEOS</NuxtLink>
    <NuxtLink to="/contact">CONTACT</NuxtLink>
    </nav>
</template>

<style lang="scss" scoped>
nav {
display: flex;
justify-content: center;
font-size: 0.8rem;
}
a {
color: inherit;
text-decoration: none;

padding: 12px;
}</style>