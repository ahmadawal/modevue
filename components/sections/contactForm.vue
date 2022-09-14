<template>
  <v-form>
    <v-row class="mb-n6">
      <v-col><v-text-field label="Nama" dense outlined></v-text-field></v-col>
      <v-col><v-text-field label="Email" dense outlined></v-text-field></v-col>
    </v-row>

    <v-row class="mb-n6">
      <v-col
        ><v-text-field label="Subject" dense outlined></v-text-field
      ></v-col>
    </v-row>
    <v-row class="mb-n6">
      <v-col>
        <v-textarea
          dense
          label="Pesan"
          auto-grow
          outlined
          rows="8"
          row-height="20"
        ></v-textarea>
      </v-col>
    </v-row>
    <v-row>
      <v-col
        ><v-btn class="my-2" color="primary">Kirim Email</v-btn
        ><v-btn class="my-2 ml-3">Hapus</v-btn></v-col
      >
    </v-row>
  </v-form>
</template>
