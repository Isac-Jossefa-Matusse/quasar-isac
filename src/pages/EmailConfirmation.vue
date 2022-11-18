<template>
  <q-page class= padding>
    <p class="text-body1">
      Obrigado por se resgistar !
    </p>
    <p class="text-body1">
      Por favor confima o email para finalizar o resgistro: <strong>{{ $route.query.email }}</strong>
    </p>

  </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'PageEmailConfirmation'
})
</script>
