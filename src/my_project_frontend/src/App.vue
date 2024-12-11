<template>
    <div class="container mx-auto flex flex-col items-center justify-center gap-16 px- bg-gray-950">
        <Header />
        <Calculator />
    </div>
</template>

<script> 
import Calculator from "./components/Calculator.vue";
import Header from "./components/Header.vue";

export default {
    name: "App",
    components: {
        Header,
        Calculator,
    },
};
</script>