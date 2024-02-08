<template>
    <div id='example-1'>
        <input v-model="message" placeholder="Enter Here">
        <p>Message: {{ message }}</p>
        <br>
        <span>Lines:</span>
        <p style="white-space: pre-line">{{ message2 }}</p>
        <textarea v-model="message2" placeholder="Enter Here"></textarea>
    </div>
    <br>
    <p>Check Box</p>
    <div id='example-2'>
        <input type="checkbox" id="checkbox" v-model="checked">
        <label for="checkbox">{{ checked }}</label>
    </div>
    <br>
    <p>Check Box2</p>
    <div id='example-3'>
        <input type="checkbox" id="jack" value="Jack" v-model="checkedNames">
        <label for="jack">Jack</label>
        <input type="checkbox" id="john" value="John" v-model="checkedNames">
        <label for="john">John</label>
        <input type="checkbox" id="mike" value="Mike" v-model="checkedNames">
        <label for="mike">Mike</label>
        <br>
        <span>Check: {{ checkedNames }}</span>
    </div>
</template>

<script>
export default {
    name: 'Input',
    template: 'Input',
    data() {
        return {
            message: [],
            message2: [],
            checked: [],
            checkedNames: []
        }
    },
};
</script>