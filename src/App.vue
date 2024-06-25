<template>
  <q-layout view="hHh lpR fFf">
    <q-header elevated>
      <q-toolbar class="custom-toolbar">

        <div class="toolbar-center">
          <q-btn-dropdown class="custom-dropdown" label="Daftar Tugas" dropdown-icon="+">
            <q-list class="nav-list">
              <q-item clickable v-close-popup>
                <router-link to="/">
                  <q-item-section>
                    <q-item-label style="color: var(--soft-green);">Weather</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
              <q-item clickable v-close-popup>
                <router-link to="/tugas1">
                  <q-item-section>
                    <q-item-label style="color: var(--soft-green);">Tugas 1</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
              <q-item clickable v-close-popup>
                <router-link to="/tugas2">
                  <q-item-section>
                    <q-item-label style="color: var(--soft-green);">Tugas 2</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
              <q-item clickable v-close-popup>
                <router-link to="/tugas3">
                  <q-item-section>
                    <q-item-label style="color: var(--soft-green);">Tugas 3</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
              <q-item clickable v-close-popup>
                <router-link to="/tugas4">
                  <q-item-section>
                    <q-item-label style="color: var(--soft-green);">Tugas 4</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
              <q-item clickable v-close-popup>
                <router-link to="/tugas5">
                  <q-item-section>
                    <q-item-label style="color: var(--soft-green);">Tugas 5</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
              <q-item clickable v-close-popup>
                <router-link to="/tugas6">
                  <q-item-section>
                    <q-item-label style="color: var(--soft-green);">Tugas 6</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
              <q-item clickable v-close-popup>
                <router-link to="/tugas7">
                  <q-item-section>
                    <q-item-label style="color: var(--soft-green);">Tugas 7</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
            </q-list>
          </q-btn-dropdown>
        </div>

      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view></router-view>
    </q-page-container>
  </q-layout>
</template>

<script>
export default {
  setup() {

  },
};
</script>

<style>
@import './assets/index.css';

.custom-toolbar {
  background-color: var(--light-gray);
  color: var(--soft-green);
  text-decoration: none;
  display: flex;
  justify-content: center;
  align-items: center;
  border: 1px dotted var(--soft-green);
}

.toolbar-center {
  display: flex;
  justify-content: center;
  width: 100%;
}

.custom-dropdown {
  background-color: var(--medium-gray); 
  color: var(--soft-green);
  border: 1px dotted var(--soft-green);
}

.nav-list {
  background-color: var(--light-gray);
  border: 2px dotted var(--soft-green);
  color: var(--soft-green);
  text-align: center;
}

.q-item-section {
  color: var(--medium-gray) !important;
}
</style>
