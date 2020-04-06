<template>
  <div>
    <div class="home">
      <Navigation />
      <v-row class="box-page">
        <template class="d-flex">
          <v-col class="justify-xl-space-around">
            <div class="nick-name">Andriar</div>
            <div class="name">Mafazan Rizkiansah</div>
            <div class="department">Software Engineer</div>
            <div class="button-group">
              <v-btn class="mr-2 mt-2" tile outlined color="#FFFFFF" small>
                <v-icon small left>mdi-message</v-icon>Hire me !
              </v-btn>
              <v-btn class="mr-2 mt-2" tile outlined color="#FFFFFF" small>Portofolio</v-btn>
            </div>
          </v-col>
          <!-- <v-col>
            <div class="name">isi dari elu</div>
          </v-col>-->
        </template>
      </v-row>
      <div class="description">
        <div>
          Hi !, My name is Andriar. I have experience in working on team for
          planning and executing a project using agile framework in developing
          applications.
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Navigation from "@/components/Navigation";
export default {
  name: "Home",
  components: {
    Navigation
  }
};
</script>
