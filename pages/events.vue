<script setup>
    const events = ref([
        {
            place: "Ergo Arena",
            date: "March 27, 2023",
            sold: true,
        },
        {
            place: "Lysaker Arena",
            date: "April 9, 2023",
            sold: true,
        },
        {
            place: "Staples Center",
            date: "May 17, 2023",
            sold: false
        }
    ])
</script>

<template>
    <PageTitle>Events</PageTitle>
    <main>
        <Event v-for="event in events" :place="event.place" :date="event.date" :sold="event.sold"></Event>
    </main>
</template>

<style scoped>
main {
    margin: 0 auto;
    width: min(100%, 560px);
    font-size: 20px;
}
</style>