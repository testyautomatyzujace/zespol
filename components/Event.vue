<script setup>
const props = defineProps(['place', 'date', 'sold'])
</script>

<template>
    <li>
        <div>{{ place }}</div>
        <div class="date">{{ date }}</div>
        <div class="link">{{ sold ? 'Sold out' : 'Shop tickets' }}</div>
    </li>
</template>

<style scoped>
.date {
color: #bec7ca
}

.link {
color: #C4ECF9;
}
</style>