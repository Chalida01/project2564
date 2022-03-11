<template>
  <div>
    <v-toolbar block color="amber darken-3">
      <v-toolbar-title>พฤติกรรมนักเรียน</v-toolbar-title>
      <v-spacer />
      <v-btn tile color="#000000">
        <v-icon left>
          mdi-pencil
        </v-icon>
        Edit
      </v-btn>
    </v-toolbar>
    <v-col
      cols="12"
      sm="6"
      md="4"
    >
      <v-text-field
        placeholder="พฤติกรรมที่ดี"
        outlined
        dense
        light
      />
      <v-text-field
        placeholder="พฤติกรรมที่ต้องปรับปรุง"
        outlined
        dense
        light
      />
      <v-text-field
        placeholder="ปัญหา/แนวทางการแก้ปัญหาร่วมกัน
ระหว่างครูที่ปรึกษากับผู้ปกครอง"
        outlined
        dense
        light
      />
      <v-text-field
        placeholder="ความคิดเห็นของผู้ปกครองที่มีต่อนักเรียน"
        outlined
        dense
        light
      />
      <v-text-field
        placeholder="ความคิดเห็นและข้อเสนอแนะของ
ครูที่ปรึกษาในการออกเยี่ยมบ้านครั้งนี้"
        outlined
        dense
        light
      />
      <v-text-field
        placeholder="อื่นๆ"
        outlined
        dense
        light
      />
      <v-btn
        :loading="loading3"
        :disabled="loading3"
        color="amber darken-3"
        class="ma-2 white--text"
        @click="loader = 'loading3'"
      >
        Upload
        <v-icon
          right
          dark
        >
          mdi-cloud-upload
        </v-icon>
      </v-btn>
      <v-img src="../img/images.png" class="image" width="350" height="150" />
    </v-col>
  </div>
</template>
<script>
export default {
  layout: 'de2'
}
</script>
