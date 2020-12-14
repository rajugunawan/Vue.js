<template>
    <div class="home">
        <HeaderShayna/>
        <HeroSection/>
        <BannerSheyna/>
        <InstagramComponent/>
        <PartnerShayna/>
        <FooterSheyna/>

     
    </div>

    
</template>


<script>

import HeaderShayna from '@/components/HeaderShayna.vue';
import HeroSection from '@/components/HeroSection.vue';
import BannerSheyna from '@/components/BannerSheyna.vue';
import InstagramComponent from '@/components/InstagramComponent';
import PartnerShayna from '@/components/PartnerShayna';
import FooterSheyna from '@/components/FooterSheyna';


export default {

    name: 'Home',
    components: {
        HeaderShayna,
        HeroSection,
        BannerSheyna,
        InstagramComponent,
        PartnerShayna,
        FooterSheyna
    }
    
};
</script>