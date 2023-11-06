<template>
  <div class="main-content">
    <BreadCrum />
<!--    <Address />-->
    <ContactForm />
    <Map/>
    <SupportTitle/>
    <Support/>
    <Accordion/>
    <Footer />
  </div>
</template>

<script>
import BreadCrum from '../../components/ContactUs/BreadCrum'
import Address from '../../components/ContactUs/Address'
import ContactForm from '../../components/ContactUs/ContactForm'
import Footer from '../../components/ContactUs/Footer'
import { themes } from '../../assets/app/app'
import Accordion from "~/components/ContactUs/Accordion.vue";
import Support from "~/components/ContactUs/Support.vue";
import SupportTitle from "~/components/ContactUs/SupportTitle.vue";
import Map from "~/components/ContactUs/Map.vue";
export default {
  layout: 'Pages',
  components: {
    Map,
    SupportTitle,
    Support,
    Accordion,
    BreadCrum,
    Address,
    ContactForm,
    Footer
  },
  mounted () {
    setTimeout(function () {
      themes.index()
    }, 0)
  }
}
</script>
