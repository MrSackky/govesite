<template>
  <v-app>
    <v-main>
      <v-container fluid>
        <!-- <navbars /> -->
        <slide />
        <spot/>
        <feaure />
        <pricing/>
        <login/>
        <contact />
      </v-container>
    </v-main>
    <foot/>
  </v-app>
</template>

<script>
import slide from "@/components/slide.vue";
// import navbars from '~/components/navbars.vue';
import foot from '~/components/foot.vue';
import contact from '~/components/contact.vue';
import spot from '~/components/spot.vue';
import feaure from '~/components/feaure.vue';
import pricing from '~/components/pricing.vue';
import login from '~/components/login.vue';
export default {
  components: {
    slide,
    // navbars,
    foot,
    contact,
    spot,
    feaure,
    pricing,
    login
  }
}
</script>
