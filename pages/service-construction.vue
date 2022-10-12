<template>
  <div>
    <NavThree />
    <PageHeader title="Construction Material Supply" />
    <ServiceConstruction />
    <FooterTwo />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import FooterTwo from "../components/FooterTwo";
  import PageHeader from "../components/PageHeader";
  import SingleService from "../components/SingleService";
  import ServiceConstruction from "../components/ServiceConstruction";
  import NavTwo from "../components/NavTwo";
  import NavThree from "~/components/NavThree";
  export default {
    components: {
      NavThree,
      ServiceConstruction,
      PageHeader,
      FooterTwo,
      NavTwo
    },
    head(){
      return {
        title: "AFAK Tanzania | Construction Material Supply"
      }
    }
  }
</script>
