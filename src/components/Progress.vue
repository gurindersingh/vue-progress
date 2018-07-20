<template>
    <div class="progress">
        <span class="progress-bar"><span class="progress-in" :style="style"></span></span>
    </div>
</template>

<script>
    export default {
        name: "vue-progress-bar",

        props: ['progress'],

        computed: {
            style() {
                return {
                    width: this.progress + '%'
                }
            }
        }
    }
</script>