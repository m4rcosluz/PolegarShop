<template>
    <VueElementLoading spinner="bar-fade-scale" color="#FD8B0E" :active="props.isActive" :is-full-screen="false" />
</template>

<script>
import VueElementLoading from 'vue-element-loading';

export default {
    name: "LoadingContentComponent",
    components: { VueElementLoading },
    props: ['props'],
    data() {
        return {
            isActive: false
        }
    }
}
</script>