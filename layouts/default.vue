<template>
  <v-card
    class="mx-auto overflow-hidden"
    height="400"
  >
    <v-app-bar
      color="#FFB300"
    >
      <v-app-bar-nav-icon color="#000000" @click="drawer = true" />
      <h1 class="tet1">
        รายชื่อนักเรียน
      </h1>
    </v-app-bar>

    <v-navigation-drawer
      v-model="drawer"
      absolute
      temporary
    >
      <v-list
        nav
        dense
      >
        <v-list-item-group
          v-model="group"
          active-class="deep-purple--text text--accent-4"
        >
          <v-list-item>
            <v-list-item-icon>
              <v-icon>mdi-home</v-icon>
            </v-list-item-icon>
            <v-list-item-title>หน้าแรก</v-list-item-title>
          </v-list-item>

          <v-list-item>
            <v-list-item-icon>
              <v-icon>mdi-account</v-icon>
            </v-list-item-icon>
            <v-list-item-title>การเยี่ยมบ้าน</v-list-item-title>
          </v-list-item>
        </v-list-item-group>
      </v-list>
    </v-navigation-drawer>
    <Nuxt />
  </v-card>
</template>
<script>
export default {
  data: () => ({
    drawer: false,
    group: null
  })
}
</script>

<style>
.tet1{
  font-family: "malgun gothic";
  font-size: 20px;
  color: #000;
}
</style>
