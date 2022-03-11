<template>
  <div class="text-center">
    <v-img src="../img/home2.png" class="image" />
    <p class="text1">
      แอพพลิเคชั่นเยี่ยมบ้านนักเรียน
    </p>
    <br><v-btn color="amber darken-3" href="/login">
      login
    </v-btn><br>
  </div>
</template>
<script>
export default {
  layout: 'theme2'
}
</script>

// แบบเขียนcss
<style>
  .image{
    width: 130px;
    margin: auto;
    margin-top: 40%;
  }
  .text1{
    font-size: 20px;
    font-family: 'malgun gothic';
    color: #000;
  }
</style>
