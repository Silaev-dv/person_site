<template>
    <section class="features">
            <section>
                <h3>Мои качества</h3>
                <ul>
                    <li>Исполнительность</li>
                    <li>Ответственность</li>
                    <li>Сдержанность</li>
                    <li>Честность</li>
                    <li>Аккуратность</li>
                </ul>
            </section>
            <section class="span"></section>
            <section>
                <h3>Мои цели</h3>
                <ul>
                    <li>Получение навыков проектирования и разработки сложных программно-аппаратных систем</li>
                    <li>Получение опыта работы на техническом предприятии</li>
                    <li>Улучшение существующих систем для снижения их себестоимости</li>
                    <li>Борьба с рекламой в интернете</li>
                    <li>Разработка новых социально-экономических ПАК</li>
                </ul>
            </section>
        </section>
</template>

<script>

export default {
    name: "SectionFeatures",
}

</script>

<style lang="scss">
.features {
    margin: 0 auto;
    text-align: left;
    display: grid;
    grid-template-columns: 29% 2% 69%;
    max-width: 1000px;

    section {
        background-color: burlywood;
        border-radius: 15px;
        opacity: 90%;
        padding: 15px;
        font-size: medium;
        
    }
    .span {
        background-color: transparent;
    }
    ul {
        list-style: inside square;
    }
}

@media (max-width: 730px) {
    .features {
        display: grid;
        grid-template-columns: 100%; 
    }
}

</style>