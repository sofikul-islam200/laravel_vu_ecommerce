<template>
     <div class="mt-4 mb-5">
          <SmallBanner></SmallBanner>
          <ProductArea></ProductArea>
          <MostPopulerProduct></MostPopulerProduct>
          <RandomProduct></RandomProduct>
          <ProductCountSection></ProductCountSection>
          <BlogPostSection></BlogPostSection>
          <NewsLatterSection></NewsLatterSection>
     </div>
</template>

<script>
//======= import all other component =======//
import SmallBanner from "./innerComponents/SmallBanner.vue";
import ProductArea from "./innerComponents/ProductArea.vue";
import MostPopulerProduct from "./innerComponents/MostPopulerProduct.vue";
import RandomProduct from "./innerComponents/RandomProduct.vue";
import ProductCountSection from "./innerComponents/ProductCountSection.vue";
import BlogPostSection from "./innerComponents/BlogPostSection.vue";
import NewsLatterSection from "./innerComponents/NewsLatterSection.vue";

export default  {
    components:{
       SmallBanner,
       ProductArea,
       MostPopulerProduct,
       RandomProduct,
       ProductCountSection,
       BlogPostSection,
       NewsLatterSection  
    },
    data(){
        return{

        }
    },

    created(){

    },
    methods:{

    }
}
</script>
