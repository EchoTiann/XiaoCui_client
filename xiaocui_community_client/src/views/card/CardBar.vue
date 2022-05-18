<template>
  <section>
    <login-welcome />

    <tip-card />

    <PromotionCard />
  </section>
</template>

<script>

import TipCard from '@/views/card/Tip'
import PromotionCard from '@/views/card/Promotion'
import LoginWelcome from '@/views/card/LoginWelcome'

export default {
  name: 'CardBra',
  components: {
    LoginWelcome, PromotionCard, TipCard
  }
}
</script>
