<template>
    <div class="main">
        <div></div>
        <h1 class="header">ZESPOL</h1>
        <div class="footer">upcoming events</div>
    </div>
</template>

<style lang="scss" scoped>
.main {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;

    flex-grow: 1;
}

h1 {
font-size: 4rem;
}

.footer {
justify-content: flex-end;
color: var(--primary);
}
</style>