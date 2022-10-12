<template>
  <div>
    <NavThree />
    <PageHeader title="Professional Consultancy" />
    <ServiceProfessionalConsultancy />
    <FooterTwo />
  </div>
</template>

<script>

import Nav from "../components/Nav";
import FooterTwo from "../components/FooterTwo";
import PageHeader from "../components/PageHeader";
import SingleService from "../components/SingleService";
import ServiceLogistics from "../components/ServiceLogistics";
import ServiceProfessionalConsultancy from "../components/ServiceProfessionalConsultancy";
import NavTwo from "../components/NavTwo";
import NavThree from "~/components/NavThree";
export default {
  components: {
    NavThree,
    ServiceProfessionalConsultancy,
    PageHeader,
    FooterTwo,
    NavTwo
  },
  head(){
    return {
      title: "AFAK Tanzania | Professional Consultancy"
    }
  }
}
</script>
