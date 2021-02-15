<template>
  <v-container>
    <v-row>
      <v-col md="12">
        <project-create-form></project-create-form>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import { mapGetters } from "vuex";

// import { ValidationObserver, ValidationProvider } from "vee-validate";

export default {
  layout: "dashboard-layout",
  data: () => ({}),
  computed: mapGetters({}),
  mounted() {}
};
</script>
