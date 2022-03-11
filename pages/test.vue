<template>
  <div>
    <v-btn block color="amber darken-3" href="/test1">
      <h2>ข้อมูลส่วนตัวนักเรียน</h2>
    </v-btn>
    <div style="margin: 3%;">
      <v-col>
        <v-img src="../img/b1.png" class="image" width="100" height="110" />
        <br>
        <p>ชื่อ นางสาวชลิดา สกุล รวดเร็ว</p>
        <p>บ้านเลขที่ xxxx ถนน xx ตำบล xxx อำเภอ xxxx จังหวัด xxxx</p>
        <p>ชื่อ-สกุลบิดา xxxxxxx xxxxxx</p>
        <p>ชื่อ-สกุลมารดา xxxxxxx xxxxxx</p>
        <p>โทรศัพท์ xxxxxxxxxx</p>
        <v-img src="../img/s11.png" class="image" width="300" height="200" />
      </v-col>
      <v-col />
    </div>
  </div>
</template>

<script>
export default {
  layout: 'de1'
}
</script>
