<template>
    <PageTitle>Contact</PageTitle>
    <main class="container">
    <form>
        <input class="input" type="text" placeholder="Name" />
        <input class="input" type="text" placeholder="E-mail" />
        <input class="input" type="text" placeholder="Message" />
        <button class="btn">SEND</button>
    </form>
    CONTACT DETAILS<br>
    BIEDRONKA.PL<br>
    E-MAIL: zespol@biedronka.pl
    </main>
</template>

<style scoped>
.input {
    all: unset;
    color: white;
    border-bottom: 3px solid #C4ECF9;

    padding: 0;
    margin: 8px 0;
}

.input::placeholder {
    color: #C4ECF9;
    opacity: 1;
}

.btn {
    all: unset;
    display: block;
    cursor: pointer;
}

.btn:hover {
    text-decoration: underline;
}

</style>