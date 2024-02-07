<template>
    <input :id="id" :ref="id" :type="type" :placeholder="placeholder" :value="formatInput(value)"/>
</template>

<script>
export default {
    props: ["id", "label", "type", "placeholder", "value", "validType"],
};
</script>