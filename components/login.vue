<template>
  <v-card class="mx-auto mt-4 mb-16" style="width: 500px; height: 640px">
    <div class="content mt-4 mr-4 ml-4 mb-4">
      <div class="menu-list mt-16 mb-16">
        <v-row
          ><v-col class="text-left">
            <a href="/" class="text-decoration-none black--text mr-2 ml-2"
              ><span class="bi-arrow-left mx-1"> กลับหน้าหลัก </span>
            </a></v-col
          ><v-col class="text-right">
            <a
              href="/register"
              class="text-decoration-none black--text mr-2 ml-2"
            >
              ยังไม่บัญชีผู้ใช้ ? <b>สมัครสมาชิก</b>
            </a></v-col
          ></v-row
        >
      </div>
      <v-card-text>
        <div class="card-body login-card-body">
          <h1 class="login-box-msg mb-3">เข้าสู่ระบบ</h1>
          <p class="login-box-msg">
            เข้าสู่ระบบเพื่อใช้งานระบบเว็บไซต์หน่วยงานสำเร็จรูป
          </p>
        </div>

        <v-text-field
          outlined
          type="email"
          class="form-control"
          placeholder="Username"
        />

        <v-text-field
          outlined
          type="password"
          class="form-control"
          placeholder="Password"
        />

        <input type="checkbox" id="remember" />
        <label for="remember"> จดจำฉัน </label>
      </v-card-text>

      <div class="text-center">
        <v-btn to="#" class="success mx-2 mb-4"> เข้าสู่ระบบ </v-btn>
        <a href="/" class="text-decoration-none black--text">
          <p>ลืมรหัสผ่าน?</p>
        </a>
      </div>
    </div>
  </v-card>
</template>

<script>
export default {
  name: "login",
};
</script>