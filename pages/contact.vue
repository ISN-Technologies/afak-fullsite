<template>
  <div>
    <NavThree />
    <PageHeader title="Contact us" />
    <ContactPage />
    <FooterTwo />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import FooterTwo from "../components/FooterTwo";
  import PageHeader from "../components/PageHeader";
  import ContactPage from "../components/ContactPage";
  import GMap from "../components/GMap";
  import Footer from "../components/Footer";
  import NavTwo from "../components/NavTwo";
  import NavThree from "~/components/NavThree";
  export default {
    components: {
      NavThree,
      FooterTwo,
      ContactPage,
      PageHeader,
      NavTwo
    },
    head(){
      return {
        title: "AFAK Tanzania | Contact Us"
      }
    }
  }
</script>
