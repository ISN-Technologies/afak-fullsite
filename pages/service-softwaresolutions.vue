<template>
  <div>
    <NavThree />
    <PageHeader title="Software Solutions" />
    <ServiceSoftwareSolutions />
    <FooterTwo />
  </div>
</template>

<script>

import Nav from "../components/Nav";
import FooterTwo from "../components/FooterTwo";
import PageHeader from "../components/PageHeader";
import SingleService from "../components/SingleService";
import ServiceLogistics from "../components/ServiceLogistics";
import ServiceSoftwareSolutions from "../components/ServiceSoftwareSolutions";
import NavTwo from "../components/NavTwo";
import NavThree from "~/components/NavThree";
export default {
  components: {
    NavThree,
    ServiceSoftwareSolutions,
    PageHeader,
    FooterTwo,
    NavTwo
  },
  head(){
    return {
      title: "AFAK Tanzania | Software Solutions"
    }
  }
}
</script>
