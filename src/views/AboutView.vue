<template>
  <div class="mt-16">
    <div class="bgimg">
      <v-container>
        <h1 class="text-center text-white">Антофобия</h1>
        <v-card class="py-6 px-6 my-8" elevation="10">
          <v-card-text class="my-5 text-justify">
            <p>
              Антофо́бия (от др.-греч. νθος «цветок» и φόβος «страх») — это
              устойчивый иррациональный страх перед цветами. Люди, страдающие
              этим типом фобии, как правило, испытывают страх не перед всеми
              цветами, а перед отдельными видами, помещёнными в цветочные
              горшки.
            </p>
          </v-card-text>
        </v-card>
      </v-container>
    </div>
    <hr />

    <v-container class="my-8">
      <v-row justify="space-between">
        <v-col cols="12" sm="7"
          ><h2 class="text-center">Антофо́бия</h2>
          <v-card-text class="my-5 text-justify">
            <p>
              Антофо́бия (от др.-греч. νθος «цветок» и φόβος «страх») — это
              устойчивый иррациональный страх перед цветами. Люди, страдающие
              этим типом фобии, как правило, испытывают страх не перед всеми
              цветами, а перед отдельными видами, помещёнными в цветочные
              горшки.
            </p>
          </v-card-text>
        </v-col>
        <v-col cols="12" sm="4">
          <v-card class="ma-16">
            <v-img src="https://lipsum.app/id/88/1600x900"></v-img>
          </v-card>
        </v-col>
      </v-row>

      <v-row justify="space-between" class="mt-6">
        <v-col cols="12" sm="7">
          <v-card-text class="my-5 text-justify">
            <p>
              Существует также и более тяжёлая форма антофобии, когда поражённый
              ею человек не только избегает цветов или мест, содержащих цветы,
              но и пугается при виде каких-либо компонентов цветка, например
              листка или стебля, бутона.
            </p>
          </v-card-text>
          <v-btn
            class="mt-6"
            :ripple="false"
            variant="plain"
            append-icon="mdi-chevron-right"
            color="light-blue-darken-4"
            router
            :to="`/test`"
            >Причины</v-btn
          ></v-col
        >
      </v-row>

      <v-row justify="space-between" class="mt-6">
        <v-col cols="12" sm="7"
          ><h2 class="text-center">Симптомы</h2>
          <v-card-text class="my-5 text-justify">
            <p>
              Возможные симптомы антофобии, которые могут проявиться при
              контакте с цветами: Страх или испуг; Учащённое сердцебиение;
              Головокружение; Тремор (дрожание); Сухость во рту; Затруднение
              дыхания; Панические атаки; Неспособность говорить либо ясно
              думать.
            </p>
          </v-card-text></v-col
        >
        <v-col cols="12" sm="4">
          <v-card class="ma-16">
            <v-img src="https://lipsum.app/id/35/1600x900"></v-img>
          </v-card>

          ></v-col
        >
      </v-row>

      <v-row justify="space-between" class="mt-6">
        <v-col cols="12" sm="4" class="hidden-sm-and-down">
          <v-card class="ma-16">
            <v-img src="https://lipsum.app/id/17/1600x900"></v-img>
          </v-card>
        </v-col>
        <v-col cols="12" sm="7"
          ><h2 class="text-center">Лечение</h2>
          <v-card-text class="my-5 text-justify">
            <p>
              Как и многие другие фобии, антофобию нельзя вылечить при помощи
              лекарственных средств, они могут только подавить симптомы.
              Возможные методы лечения фобии: Психотерапия;
              Когнитивно-поведенческая терапия; Поведенческая терапия (например,
              конфронтационная терапия).
            </p>
          </v-card-text></v-col
        >
        <v-col cols="12" sm="4" class="hidden-md-and-up">
          <v-card class="ma-16">
            <v-img src="https://lipsum.app/id/73/1600x900"></v-img>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
    <hr />
  </div>
</template>

<script>
export default {};
</script>

<style type="text/css">
.bgimg {
  background-image: url("../assets/bg_home.png");
  background-repeat: repeat;
}
</style>
