<template>
    <FormComponent />
</template>

<script lang="ts">
import FormComponent from '../components/FormComponent.vue'
import { defineComponent } from 'vue';
export default defineComponent({
    name: 'FormPage',
    components: {
        FormComponent
    }
})
</script>