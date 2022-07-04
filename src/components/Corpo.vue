<script setup>
</script>

<template>
    <section id="corpo">
        <img src="../assets/dog.jpg">
        <div>
            <div>Seu nome</div>
            <p>Coloque aqui sua biografia de forma resumida. Coloque aqui sua biografia de forma resumida.
                Coloque aqui sua biografia de forma resumida. Coloque aqui sua biografia de forma resumida
                Coloque aqui sua biografia de forma resumida.
            </p>
        </div>
    </section>
</template>
<style>
section#corpo {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    padding: 50px;
}

section#corpo div {
    text-align: left;
}

section#corpo div div {
    font-size: 65px;
}

section#corpo div p {
    max-width: 460px;
}

section#corpo img {
    border-radius: 50%;
    max-height: 150px;
}
</style>
