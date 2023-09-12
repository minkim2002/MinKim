<template>
    <div class="text-left">
        <v-dialog v-model="dialog" width="auto">
            <template v-slot:activator="{ props }">
                <v-btn v-btn color="#958b00" dark text class="ml-n4" v-bind="props" @click="dialog = true">
                    Know More
                    <v-icon right>mdi-arrow-right</v-icon>
                </v-btn>
            </template>

            <v-carousel>
                <v-carousel-item src="taekwondo.png" cover></v-carousel-item>
                <v-carousel-item src="travel.png" cover></v-carousel-item>
                <v-carousel-item src="pull-up.png" cover></v-carousel-item>
                <v-carousel-item src="bike.png" cover></v-carousel-item>
                <v-carousel-item src="music.png" cover></v-carousel-item>
            </v-carousel>
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
<style></style>