<template>
  <div class="slide mb-3" id="slide">
    <navbars />
    <v-row class="col-right grey lighten-4 text-no-wrap">
      <v-col class="grey lighten-2 text-no-wrap rounded-r-xl">
        <div class="text-right mt-16 mb-16 mr-8">
          <h1 class="head mb-4">ระบบเว็บไซต์หน่วยงานสำเร็จรูป</h1>
          <p>
            สร้างไซต์หน่วยงานท่านได้ตัวเอง ง่าย เร็ว สวยงาม<br />MANAGE YOUR
            ORGANIZATION , EASY , FAST , BEAUTIFUL
          </p>
          <v-btn class="success mt-4 mb-4" to="/register">ทดลองใช้งาน</v-btn>
          <p class="red--text">* สมัครใช้งานวันนี้ทดลองใช้ฟรี 30วัน</p>
        </div>
      </v-col>
      <v-col class="col-left d-none d-md-flex">
        <v-layout justify-center align-center>
          <img
            class="picleft"
            width="400px"
            height="320px"
            src="https://s3-alpha-sig.figma.com/img/7c09/860c/b2e58571d299b656d2dd3e81a8baaf4e?Expires=1623628800&Signature=BYoPt-Y11sss1Vk1INGZYDb6w35yb3EztKOXTBHs8-VuBEOpFypLJNd~miF7o2kRn6a9oucqonJ0UKKSb1kkTfPWorbHODUbnH~1CUOvtuXhLTt37nVRjaFM4rUpYS-fDnJyZiGKE5WEazIBDQvhyIGQvpTlAtjYy~SoLcGw3tXSqiZ2MDDDpPrAMFlatRVJB9U2LazZcVVNP-UfJVWB4dD954RZG6QPClI3N2kbepr~WK3C1wkvLRvgcXsO1oMGAmhCjXf9XY0s~wEBL40R07oWFb~sHlRQCX46r9DTK1FDCDQ26HfRoT5F-Rh4C6XgY5VN1CiSG-u288wJ7FZEGA__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA"
          />
        </v-layout>
      </v-col>
    </v-row>
  </div>
</template>

<script>
import navbars from "~/components/navbars.vue";

export default {
  name: "slide",
  components: {
    navbars,
  },
};
</script>