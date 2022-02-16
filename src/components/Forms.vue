<template>
    <div> 

    </div>
</template>

<script>
export default {
    name: 'the-form',
    data: () => ({
        input: {
            name: '',
            email:'',
            message:'',
        },
        forms: [],
    }),

    methods: {
        submitForms() {
            this.forms.push(this.input);
            this.input = {
                name: '',
                email: '',
                message: '',
            };
        },
    },

    watch: {
        'input.name': (newValue, oldValue) => {
            if (newValue !== '') {
                console.log(oldValue);
            } else if (newValue !== oldValue) {
                console.log(newValue);
            } else {
                console.log('no change');
            }
        },
    },
};
</script>

<style lang="sass" scoped>
.paragraph
    color: red
    &.blue
        color: blue
</style>