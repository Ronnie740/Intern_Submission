<template>
  <q-layout view="hHh lpR fFf">

      <div class="flex">
      <q-toolbar>
        <q-toolbar-title>
          <q-avatar id="logo">
          
          </q-avatar>
          <q-avatar id="logo2">

          </q-avatar>
          Proom
        </q-toolbar-title>
      </q-toolbar>
  
      <q-tabs align="left">
        <q-route-tab to="#" label="Courses" />
        <q-route-tab to="#" label="Features" />
        <q-route-tab to="#" label="Support" />
      </q-tabs>
      
      <q-btn dense round flat icon="email">
      <q-badge color="red" floating transparent>
        3
      </q-badge>
    </q-btn>

    <q-avatar>
      <img src="/icons/pic_1.jpg" width="20px" height="20px">
    </q-avatar>
    </div>

    <q-page-container>
      <router-view />
    </q-page-container>

  </q-layout>
</template>

<script>
export default {
  data () {
    return {
    }
  }
}
</script>