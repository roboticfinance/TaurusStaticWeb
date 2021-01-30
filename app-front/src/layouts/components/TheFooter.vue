<!-- =========================================================================================
    File Name: TheFooter.vue
    Description: Footer component
    Component Name: TheFooter
    ----------------------------------------------------------------------------------------
    Item Name: Vuexy - Vuejs, HTML & Laravel Admin Dashboard Template
      Author: Pixinvent
    Author URL: http://www.themeforest.net/user/pixinvent
========================================================================================== -->


<template functional>
    <footer class="the-footer flex-wrap justify-between" :class="classes">
        <span>COPYRIGHT &copy; {{ new Date().getFullYear() }} ConciseData All rights Reserved</span>
        <span class="md:flex hidden items-center">
            <span> 复杂数据，简单决策</span>
            <!--feather-icon icon="HeartIcon" svgClasses="stroke-current text-danger w-6 h-6" class="ml-2" /-->
        </span>

        <!-- buyNow component -->
        <!-- <component :is="injections.components.BuyNow"></component> -->
    </footer>
</template>

<script>
// import BuyNow from '../../components/BuyNow.vue'

export default {
    name: "the-footer",
    props: {
        classes: {
            type: String,
        },
    }/* ,
    inject: {
      components:{
          default: {
            BuyNow
          }
      }
    } */
}
</script>
