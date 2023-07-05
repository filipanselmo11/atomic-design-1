<template>
    <Molecule1/>
</template>

<script lang="ts">
import Molecule1 from './molecules/Molecule1.vue';
import { defineComponent } from 'vue';

export default defineComponent({
    name: "FormComponent",
    components: { Molecule1 }
})
</script>