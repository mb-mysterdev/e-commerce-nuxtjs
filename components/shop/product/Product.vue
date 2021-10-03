<template>
  <div class="col-lg-3 col-md-4 col-sm-6 mix women">
    <div>
      <div class="product__item">
        <div class="product__item__pic set-bg" style="background-image: url('https://i.pinimg.com/originals/41/7b/d1/417bd1ee04fe30e07f81987127676368.jpg')">
          <div v-if="isNew" class="label new">
            New
          </div>
          <ul class="product__hover">
            <li><a href="img/product/product-1.jpg" class="image-popup"><span class="arrow_expand" /></a></li>
            <li><a href="#"><span class="icon_heart_alt" /></a></li>
            <li><a href="#"><span class="icon_bag_alt" /></a></li>
          </ul>
        </div>
        <div class="product__item__text">
          <h6><a href="#">Buttons tweed blazer</a></h6>
          <div class="rating">
            <i class="fa fa-star" />
            <i class="fa fa-star" />
            <i class="fa fa-star" />
            <i class="fa fa-star" />
            <i class="fa fa-star" />
          </div>
          <div class="product__price">
            $ 59.0
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    product: {
      type: Object,
      default () {
        return { isNew: false }
      }
    }
  }

}
</script>

<style>

</style>
