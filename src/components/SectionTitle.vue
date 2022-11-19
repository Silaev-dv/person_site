<template>
    <section class="title">
            <section>
                <p>Даниил Силаев</p> 
                <p>Группа 2181 </p>
                <p>Университет Дубна</p> 
            </section>
            <aside>
                <img src="../assets/logo.png" alt="Не прогрузилось :(">
            </aside>
        </section>
</template>

<script>

export default {
    name: "SectionTitle",
}

</script>

<style lang="scss">
.title {
    text-align: center;
    margin: 0 auto;
    display: grid;
    grid-template-columns: 40% 60%;
    max-width: 1000px;

    section {
        opacity: 90%;
        border-radius: 15px;
        padding: 30px;
        font-size: large;
        background: -webkit-linear-gradient(0deg, #1eff00,#85ff75,#2c9b00);
        background: linear-gradient(0deg, #1eaf00,#85cf75,#2c9b00);
    }
}

@media (max-width: 560px) {
    .title {
        display: grid;
        grid-template-columns: 100%; 
    }
}

</style>