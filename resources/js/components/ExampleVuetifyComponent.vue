<template>
    <v-app>
        <v-card
            class="mx-auto"
            max-width="900"
        >
            <v-card-text>
                <div>Hello</div>
                <p class="display-1 text--primary">
                    This is a Vuetify card component
                </p>
                <p>Please see the example component</p>
            </v-card-text>
            <v-card-actions>
                <v-btn
                    text
                    color="deep-purple accent-4"
                    href="login"
                >
                    Login
                </v-btn>
                <v-btn
                    text
                    color="deep-purple accent-4"
                    href="register"
                >
                    Register
                </v-btn>
            </v-card-actions>
        </v-card>
    </v-app>
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
