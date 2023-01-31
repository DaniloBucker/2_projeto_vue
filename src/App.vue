<template>
    <div>
        <PrimeiroComponente />
        <p>O dado de app é: {{ testando }}.</p>
        <Life-Cycle />
    </div>
</template>
<script>
import PrimeiroComponente from './components/PrimeiroComponente.vue'
import Lifecycle from './components/LifeCycle.vue'
import LifeCicle from './components/LifeCicle.vue'
export default {
    name: 'App',
    components: {
        PrimeiroComponente,
        Lifecycle,
        LifeCicle
    }
}
</script>
