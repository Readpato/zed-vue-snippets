<script setup lang="ts">
import { ref } from "vue";
const doVueSnippetsWork = ref(false);
const doTsSnippetsWork = ref(true);
</script>

<template>
    <div>
        <h1>Do Vue snippets work? {{ doVueSnippetsWork ? "Yes" : "No" }}</h1>
        <h1>Do TS snippets work? {{ doTsSnippetsWork ? "Yes" : "No" }}</h1>
    </div>
</template>
