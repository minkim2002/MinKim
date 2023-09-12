<template>
    <div class="text-left">
        <v-dialog v-model="dialog" width="auto">
            <template v-slot:activator="{ props }">
                <v-btn color="#958b00" v-bind="props" @click="dialog = true">
                    About Me
                </v-btn>
            </template>

            <v-timeline side="end" class="about_me">
                <v-timeline-item dot-color="pink" size="small">
                    <div class="d-flex">
                        <strong class="me-4 text-center">Born and Raised in Korea</strong>
                    </div>
                </v-timeline-item>

                <v-timeline-item dot-color="teal-lighten-3" size="small">
                    <div class="d-flex">
                        <strong class="ms-4 text-center">Academic Life in Virginia</strong>
                    </div>
                </v-timeline-item>

                <v-timeline-item dot-color="pink" size="small">
                    <div class="d-flex">
                        <strong class="me-4 text-center">Web App Developer @ W&M</strong>
                    </div>
                </v-timeline-item>

                <v-timeline-item dot-color="teal-lighten-3" size="small">
                    <div class="d-flex">
                        <strong class="ms-4 text-center">My MBTI: ISTJ</strong>
                    </div>
                </v-timeline-item>
            </v-timeline>
        </v-dialog>
    </div>
</template>
<script>
export default {
    data() {
        return {
            dialog: false,
        }
    },
}
</script>
<style>
.about_me {
    background-color: #cad1e8;
}
</style>