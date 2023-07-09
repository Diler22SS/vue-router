<template>
  <div class="mt-16">
    <div class="bgimg">
      <v-container>
        <p class="text-center text-white">
          Антофо́бия (от др.-греч. νθος «цветок» и φόβος «страх») — это
          устойчивый иррациональный страх перед цветами. Люди, страдающие этим
          типом фобии, как правило, испытывают страх не перед всеми цветами, а
          перед отдельными видами, помещёнными в цветочные горшки.Существует
          также и более тяжёлая форма антофобии, когда поражённый ею человек не
          только избегает цветов или мест, содержащих цветы, но и пугается при
          виде каких-либо компонентов цветка, например листка или стебля,
          бутона.
        </p>
      </v-container>
    </div>
    <hr />
    <v-container class="my-8">
      <v-card class="ma-16"> <v-img src="https://lipsum.app/id/79/1600x900"></v-img> </v-card>
      <div class="text-center">
        <v-btn
          class="mt-6"
          :ripple="false"
          variant="plain"
          append-icon="mdi-chevron-right"
          color="light-blue-darken-4"
          router
          :to="`/test`"
          >Причины</v-btn
        >
      </div>
      >
      <h2 class="text-center">Источники</h2>

      <p>
        Definition of Fear of flowers from MedicineNet.com (12 января 2000).
        Дата обращения: 30 января 2009. Архивировано 22 июля 2012 года. lisa
        Fritscher:
        [phobias.about.com/od/phobiasatoh/f/What-Is-The-Fear-Of-Flowers.htm What
        Is the Fear of Flowers?] Источник. Дата обращения: 3 марта 2019.
        Архивировано из оригинала 28 февраля 2016 года. phobias.about.com, 2.
        August 2012; abgerufen 22. August 2013 (englisch). Symptoms of
        Anthophobia. Архивная копия от 6 марта 2019 на Wayback Machine
        rightdiagnosis.com; abgerufen 22. August 2013 (englisch). Antophobia.
        Архивная копия от 24 ноября 2018 на Wayback Machine
        allaboutcounseling.com; abgerufen 22. August 2013 (englisch). What Is
        Anthophobia? Архивная копия от 6 марта 2019 на Wayback Machine
        wisegeek.com; abgerufen 22. August 2013 (englisch).
      </p>
      <div class="text-center">
      <v-btn
        class="mt-6"
        :ripple="false"
        variant="plain"
        append-icon="mdi-chevron-right"
        color="light-blue-darken-4"
        router
        :to="`/about`"
        >Узнать больше про Антофобию</v-btn
      ></div>
      <v-card class="ma-16"> <v-img src="https://lipsum.app/id/89/1600x900"></v-img> </v-card>
    </v-container>

    <hr />
  </div>
</template>

<style type="text/css">
.bgimg {
  background-image: url("../assets/bg_home.png");
  background-repeat: repeat;
}
</style>
