<template>
    <!--<CommonHeader/>-->
    <main>
        <SectionTitle/>
        <SectionFeatures/>
    </main>
</template>

<script>
import SectionTitle from '@/components/SectionTitle.vue';
import SectionFeatures from '@/components/SectionFeatures.vue';

export default {
    components: {
    SectionTitle,
    SectionFeatures,
}
}
</script>


<style lang="scss" scoped>

section {
    padding: 15px;
}

</style>