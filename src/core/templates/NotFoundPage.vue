<template>
  <div class="text-center pa-15 max-width-container mx-auto">
    <img height="50" src="@/assets/images/logo.png" alt="logo" />
    <v-divider></v-divider>

    <div class="mt-10">
      <h1>404 | Página não encontrada</h1>
      <p>
        A página solicitada não existe,<br />
        verifique o endereço digitado e tente novamente.
      </p>

      <v-btn color="primary" to="/dashboard" class="mt-10" large
        >Voltar ao inicio</v-btn
      >
    </div>
  </div>
</template>
<script>
export default {
  name: "NotFoundPage",
};
</script>