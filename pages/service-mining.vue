<template>
  <div>
    <NavThree />
    <PageHeader title="Mining" />
    <ServiceMining />
    <FooterTwo />
  </div>
</template>

<script>

import Nav from "../components/Nav";
import FooterTwo from "../components/FooterTwo";
import PageHeader from "../components/PageHeader";
import SingleService from "../components/SingleService";
import ServiceMining from "../components/ServiceMining";
import NavThree from "~/components/NavThree";
export default {
  components: {
    NavThree,
    ServiceMining,
    PageHeader,
    FooterTwo,
    Nav
  },
  head(){
    return {
      title: "AFAK Tanzania | Mining"
    }
  }
}
</script>
