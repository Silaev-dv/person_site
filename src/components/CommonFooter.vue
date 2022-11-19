<template>
    <footer>
        <section class="links">
            <span>Ссылки</span>
            <ul>
                <li><a href="/skills">Навыки</a></li>
                <li><a href="/resume">Резюме</a></li>
                <li><a href="/portfolio">Портфолио</a></li>
                <li><a href="/contacts">Контакты</a></li>
                <li><a href="/materials">Материалы</a></li>
            </ul>
        </section>
        <section class="info">
            <span>Информация</span>
            <ul>
                <li>+7 (929) 625-38-20</li>
                <li>г. Дубна</li>
                <li>Университет Дубна</li>
                <li>ИСАУ ПМИ 2181</li>
            </ul>
        </section>
        <section class="contacts">
            <!--<ul>
                <li>Навыки</li>
                <li>Навыки</li>
                <li>Навыки</li>
                <li>Навыки</li>
            </ul>-->
        </section>
        <section class="copyright">
            <span>Created with Vue.js + SCSS technologes</span><br/>
            <span>Copyright 2022</span>
        </section>
    </footer>
</template>

<script>

export default {
    name: "CommonFooter",
}

</script>

<style lang="scss">
footer {
	width: 100%;
    text-align: left;
    display: grid;
    grid-template-columns: repeat(3, 33.333%);
    background-color: bisque;
    

    section {
        margin-top: 5px;
        margin-left: 5px;
        margin-right: 5px;
        padding: 5px;
        font-size: medium;
        ul {
            margin: 10px;
            list-style-type: none;
            padding-left: 0;
            li {
                margin: 10px;
            }
        }
    }

    .copyright {
        grid-column-start: 1;
        grid-column-end: 4;
        text-align: right;
    }
}

@media (max-width: 670px) {
    footer {
        display: grid;
        grid-template-columns: 50% 50%;
        section {
            padding: 0px;
        }
        .contacts {
            grid-column-start: 1;
            grid-column-end: 3;
        }
        .copyright{
            grid-column-start: 1;
            grid-column-end: 3;
        } 
    }
}

</style>