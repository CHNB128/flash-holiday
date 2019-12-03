<template>
  <div class="root pt-3">
    <div>
      <h3>
        <strong>Новогодние поздравления от Деда Мороза и Снегурочки</strong>
      </h3>
      <img src="/images/main.jpeg" class="img-fluid">
    </div>
    <contact-form>
      <h3>
        <strong>Веселый Дед Мороз и поющая Снегурочка</strong>
      </h3>
    </contact-form>
    <proofs/>
    <gallery/>
    <review/>
    <div class="bg-info p-3">
      sample text
      <div class="text-center">
        <button type="button" class="btn btn-primary">
          Оставить заказ
        </button>
      </div>
    </div>
   <div class="p-3">
      <img src="/images/sales.jpeg" class="img-fluid">
      текст
      Сказочную скидку
      <div class="text-center">
        <button type="button" class="btn btn-primary">
          Получить скидку
        </button>
      </div>
    </div>
    <div class="bg-info p-3">
      <h2>Наши цены</h2>
      <div>
        Цены
      </div>
    </div>
    <div class="p-3"></div>
    <contact-form>
      <div>
        sample text
      </div>
    </contact-form>
    <div class="p-3"></div>
  </div>
</template>

<script>
import ContactForm from '@/components/ContactForm'
import Review from '@/components/Review'
import Gallery from '@/components/Gallery'
import Proofs from '@/components/Proofs'

export default {
  name: 'home',
  components: {
    ContactForm,
    Review,
    Proofs,
    Gallery
  }
}
</script>

<style lang="scss" scoped>
.root {
  display: flex;
  flex-direction: column;
}
</style>
