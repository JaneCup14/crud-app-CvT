<template>
    <!--
        <b-navbar toggleable="lg" type="dark" variant="primary">
        <b-container>
            <b-row class="text-white">
                <b-col>
                    <b-icon-people-fill class="h2"></b-icon-people-fill>
                </b-col>
                <b-col>
                    <span class="h3">CRM</span>
                </b-col>
            </b-row>
        </b-container>
    </b-navbar>
    -->

    <v-app-bar app color="cyan darken-2" dark>
        <v-toolbar-title>Seznam dárců</v-toolbar-title>
        <v-spacer></v-spacer>
        <v-btn color="blue-grey lighten-2">Přidat dárce</v-btn>
    </v-app-bar>
</template>

<script>
export default {
    name: "PageHeader",
};
</script>
