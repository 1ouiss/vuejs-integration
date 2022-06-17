<template>
    <div id="mainContainer">
        <MainComponentVue :title="title"></MainComponentVue>
        <AsideComponentVue :title="title"></AsideComponentVue>
    </div>
    <FooterComponentVue></FooterComponentVue>
</template>

<script>
import MainComponentVue from '@/components/MainComponent.vue'
import FooterComponentVue from '@/components/FooterComponent.vue'
import AsideComponentVue from '@/components/AsideComponent.vue'
export default{
    name: 'ProfilView',
    components: {
        MainComponentVue,
        FooterComponentVue,
        AsideComponentVue
    },
    data() {
        return {
            title: 'Profil'
        }
    }
}
</script>