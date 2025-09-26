
<template>
  <v-container fluid class="d-flex align-center justify-center fill-height">
    <v-card
      class="pa-8 rounded-xl"
      elevation="8"
      max-width="400"
    >
      <v-card-title class="text-h5 text-center mb-4">
        Iniciar Sesión
      </v-card-title>

      <v-card-text>
        <v-text-field
          label="Correo electrónico"
          prepend-inner-icon="mdi-email"
          variant="outlined"
          density="comfortable"
          class="mb-4"
        />

        <v-text-field
          label="Contraseña"
          type="password"
          prepend-inner-icon="mdi-lock"
          variant="outlined"
          density="comfortable"
        />
      </v-card-text>

      <v-card-actions class="d-flex flex-column">
        <v-btn
          block
          color="primary"
          class="mb-2"
          size="large"
        >
          Entrar
        </v-btn>

        <v-btn
          variant="text"
          size="small"
          color="secondary"
        >
          ¿Olvidaste tu contraseña?
        </v-btn>
      </v-card-actions>
    </v-card>
  </v-container>
</template>

<style scoped>
.fill-height {
  height: 100vh;
  background: linear-gradient(135deg, #1976d2, #42a5f5);
}
</style>