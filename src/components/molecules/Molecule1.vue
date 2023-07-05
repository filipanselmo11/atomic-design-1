<template>
    <AtomLabel/>
    <AtomInput/>
    <AtomButtom/>
</template>
import AtomLabel from '../atoms/AtomLabel.vue';

<script lang="ts">
import AtomButtom from '../atoms/AtomButton.vue'
import AtomInput from '../atoms/AtomInput.vue'
import AtomLabel from '../atoms/AtomLabel.vue'
import { defineComponent } from 'vue';
export default defineComponent({
    name: 'Molecule1',
    components: {
    AtomButtom,
    AtomInput,
    AtomLabel,
},
    data() {
        return{}
    }
})
</script>