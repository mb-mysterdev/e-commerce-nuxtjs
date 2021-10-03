<template>
  <div>
    <!-- Categories Section Begin -->
    <section class="categories">
      <div class="container-fluid">
        <div class="row">
          <div class="col-lg-12 p-0">
            <div
              class="categories__item categories__large__item set-bg"
              style="background-image: url('https://cdn.pixabay.com/photo/2018/05/21/04/40/vape-3417375_1280.jpg')"
            >
              <div class="categories__text">
                <h1>Vape website </h1>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Categories Section End -->
    <section>
      <div v-for="i in 10" :key="i" class="row property__gallery">
        <product :key="i" />
      </div>
    </section>
  </div>
</template>

<script>
import Product from '~/components/shop/product/Product.vue'
export default {
  name: 'Index',
  components: { Product }
}
</script>
