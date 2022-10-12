<template>
  <div>
    <NavThree />
    <PageHeader title="Our Services" />
    <ServicePage />
    <FooterTwo />
  </div>
</template>

<script>

  import FooterTwo from "../components/FooterTwo";
  import PageHeader from "../components/PageHeader";
  import ServicePage from "../components/ServicePage";
  import NavTwo from "../components/NavTwo";
  import NavThree from "~/components/NavThree";
  export default {
    components: {
      NavThree,
      ServicePage,
      PageHeader,
      FooterTwo,
      NavTwo
    },
    head(){
      return {
        title: "AFAK Tanzania | Our Services"
      }
    }
  }
</script>
