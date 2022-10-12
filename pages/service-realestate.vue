<template>
  <div>
    <NavThree />
    <PageHeader title="Real Estate" />
    <ServiceRealEstate />
    <FooterTwo />
  </div>
</template>

<script>

import Nav from "../components/Nav";
import FooterTwo from "../components/FooterTwo";
import PageHeader from "../components/PageHeader";
import SingleService from "../components/SingleService";
import ServiceLogistics from "../components/ServiceLogistics";
import ServiceRealEstate from "../components/ServiceRealEstate";
import NavTwo from "../components/NavTwo";
import NavThree from "~/components/NavThree";
export default {
  components: {
    NavThree,
    ServiceRealEstate,
    PageHeader,
    FooterTwo,
    NavTwo
  },
  head(){
    return {
      title: "AFAK Tanzania | Real Estate"
    }
  }
}
</script>
