<template>
    <HeaderView />
    <div class="container">
        <router-view />
    </div>
</template>


<script>
import HeaderView from "@/components/HeaderView.vue";
export default {
    components: {
        HeaderView,
    },
};
</script>
