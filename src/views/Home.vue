<template>
  <div class="home">
    <TeknikHeader />
    <HeroCarousel />
    <WomenBanner />
    <InstaTeknik />
    <PartnerTeknik />
    <FooterTeknik />
  </div>
</template>

<script>
// @ is an alias to /src
import TeknikHeader from '@/components/TeknikHeader.vue';
import HeroCarousel from '@/components/HeroCarousel.vue';
import WomenBanner from '@/components/WomenBanner.vue';
import InstaTeknik from '@/components/InstaTeknik.vue';
import PartnerTeknik from '@/components/PartnerTeknik.vue';
import FooterTeknik from '@/components/FooterTeknik.vue';

export default {
  name: 'Home',
  components: {
    TeknikHeader,
    HeroCarousel,
    WomenBanner,
    InstaTeknik,
    PartnerTeknik,
    FooterTeknik,
  },
};
</script>
