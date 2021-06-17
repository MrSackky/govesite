<template>
  <v-app-bar app fixed>
    <v-row>
      <v-col>
        <div class="logo-btn">
          <a class="navbar-brand" href="#">
            <img
              class="mt-1"
              src="https://s3-alpha-sig.figma.com/img/f3a8/828d/c89176f9a2b21f7594514cf37464f3f2?Expires=1623628800&Signature=NdzZeaTiSbe7tYByVABtpyOxGVceW2S-suXc5MB~oYy8xTm5Em5faWRA7KSGaecO661tbOIw2Bu9oBy4getfCVcWTTlMLl9rpmEfe3e1m5CpoSzqlVrFFqJlHM22vqKjYoC473cOhPnZqyEHPhxoPvmJCSK6Mexr-XV3fRAhz-Ra4YJz7DMQpy1K0Kl1F-XPDpjfxSpTNWJ97cmRpGD6WJxLPxUJkM92ai6XDNJPnCw-my4VYRlJPqhE-VgaO8KsmP-NyN3LFcXBIkP6XmdqKhl30E~PxBTlqrWa3TyXcKw6CdMDKnUX~giEPS4YbzZOG2U48DYXyCJbsTdiTRtwjg__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA"
              alt=""
              height="65px"
              width="auto"
          /></a>
        </div>
      </v-col>
      <v-col class="mt-8">
        <div class="btn">
          <a class="text-decoration-none black--text mr-2 ml-2" href="#spot"
            >คุณสมบัติ</a
          >
          <a class="text-decoration-none black--text mr-2 ml-2" href="#pricing"
            >แพคเกจ</a
          >
          <a class="text-decoration-none black--text mr-2 ml-2" href="#contact"
            >ติดต่อเรา</a
          >
        </div>
      </v-col>
      <v-col class="mt-6">
        <div class="text-right">
          <a href="/login" class="text-decoration-none black--text mr-1">
            เข้าสู่ระบบ </a
          >|
          <v-btn to="/register" class="success mx-2"> สมัครใช้งาน </v-btn>
        </div>
      </v-col>
    </v-row>
  </v-app-bar>
</template>

<script>
export default {
  name: "navbar"
};
</script>
