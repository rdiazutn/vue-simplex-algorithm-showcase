<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="10" md="8">
      <div class="text-center">
        <CompanyLogo src="/dieta_simplex/diet_food.png" />
      </div>
      <v-card>
        <v-card-title class="headline">
          Bienvenido a Simplex Dieta!
        </v-card-title>
        <v-card-text>
          <p> Simplex dieta es un sistema que permite generar una lista de compras que se adecúe a tus gustos!</p>
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn
            class="w-100"
            color="primary"
            nuxt
            to="/nueva_dieta"
          >
            Iniciar dieta!
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
import CompanyLogo from '~/components/General/CompanyLogo'
export default {
  components: {
    CompanyLogo
  }
}
</script>
