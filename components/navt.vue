<template>
  <v-app-bar fixed>
    <v-card-title>
      <div class="logo-btn">
        <a class="navbar-brand" href="/">
          <img
            class="mt-1"
            src="../assets/src/Logo-newgovesite.gif"
            alt=""
            height="65px"
            width="auto"
        /></a>
      </div>
    </v-card-title>

    <v-toolbar-items class="hidden-md-and-down">
      <v-col>
          <div class="btn text-center">
            <a class="text-decoration-none black--text mr-2 ml-2" href="#spot"
              >คุณสมบัติ</a
            >
            <a
              class="text-decoration-none black--text mr-2 ml-2"
              href="#pricing"
              >แพคเกจ</a
            >
            <a
              class="text-decoration-none black--text mr-2 ml-2"
              href="#contact"
              >ติดต่อเรา</a
            >
          </div>
      </v-col>
      <v-col>
        <div class="text-right">
          <NuxtLink to="../login" class="text-decoration-none black--text mr-1">
            เข้าสู่ระบบ </NuxtLink
          >|
          <v-btn to="/register" class="success mx-2"> สมัครใช้งาน </v-btn>
        </div>
      </v-col>
    </v-toolbar-items>

    <div class="hidden-md-and-up">
      <v-menu offset-y>
        <template v-slot:activator="{ on }">
          <v-app-bar-nav-icon v-on="on"></v-app-bar-nav-icon>
        </template>
        <v-list class="responsiveMenu">
          <v-list-item>
                <a href="/login" class="text-decoration-none black--text">
                เข้าสู่ระบบ
              </a>
          </v-list-item>
          <v-list-item>
              <v-btn to="/register" class="success">
                สมัครใช้งาน
              </v-btn>
          </v-list-item>
        </v-list>
      </v-menu>
    </div>
  </v-app-bar>
</template>

<script>
export default {
  name: "Header"
};
</script>
