<template>
  <q-page class="bg-indigo-1">
    <q-card class="my-card fit custom-shadow q-pb-sm bg-grey-11" bordered>
      <q-item>
        <q-item-section avatar>
          <q-avatar size="50px">
            <img src="../assets/avatar.png">
          </q-avatar>
        </q-item-section>

        <q-item-section>
          <q-item-label
            class="text-h6"
          >
            Luiz Felipe Kirchbaner
          </q-item-label>
          <q-item-label class="text-body1 text-grey-7">
            Mussum Ipsum, cacilds vidis litro abertis. Paisis, filhis, espiritis santis.
          </q-item-label>
        </q-item-section>
      </q-item>
    </q-card>
    <div class="text-body1 q-mt-xl text-center text-grey-10">
      <q-icon name="touch_app" style="font-size: 1.6rem;" />
      Toque para interagir
    </div>
    <div class="q-pa-md">
      <q-list>
        <q-item clickable v-ripple class="custom-shadow bg-grey-1 rounded-borders q-mb-lg">
          <q-item-section>
            <q-avatar
              size="60px"
              rounded
              color="deep-purple-13"
              text-color="white"
              icon="fab fa-github"
            />
          </q-item-section>
          <q-item-section class="text-h5">GitHub</q-item-section>
        </q-item>
        <q-item clickable v-ripple class="custom-shadow bg-grey-1 rounded-borders q-mb-lg">
          <q-item-section>
            <q-avatar
              size="60px"
              rounded
              color="indigo-1"
              text-color="deep-purple-13"
              icon="fab fa-discord"
            />
          </q-item-section>
          <q-item-section class="text-h5">Discord</q-item-section>
        </q-item>
        <q-item clickable v-ripple class="custom-shadow bg-grey-1 rounded-borders q-mb-lg">
          <q-item-section>
            <q-avatar
              size="60px"
              rounded
              color="deep-purple-13"
              text-color="white"
              icon="fab fa-linkedin-in"
            />
          </q-item-section>
          <q-item-section class="text-h5">Linkedin</q-item-section>
        </q-item>
        <q-item clickable v-ripple class="custom-shadow bg-grey-1 rounded-borders q-mb-lg">
          <q-item-section>
            <q-avatar
              size="60px"
              rounded
              color="indigo-1"
              text-color="deep-purple-13"
              icon="fab fa-instagram"
            />
          </q-item-section>
          <q-item-section class="text-h5">Instagram</q-item-section>
        </q-item>
      </q-list>
    </div>
  </q-page>
</template>

<script>
export default {
  name: 'PageIndex'
}
</script>

<style scoped>
.q-item__label {
  line-height: 1.5 !important;
}
.custom-shadow {
  box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
}
</style>
