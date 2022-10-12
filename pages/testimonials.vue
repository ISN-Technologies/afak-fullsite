<template>
  <div>
    <NavThree />
    <PageHeader title="Testimonials" />
    <TestimonialPage />
    <ContactArea />
    <FooterTwo />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import FooterTwo from "../components/FooterTwo";
  import PageHeader from "../components/PageHeader";
  import TestimonialPage from "../components/TestimonialPage";
  import ContactArea from "../components/ContactArea";
  import NavTwo from "../components/NavTwo";
  import NavThree from "~/components/NavThree";
  export default {
    components: {
      NavThree,
      ContactArea,
      TestimonialPage,
      PageHeader,
      FooterTwo,
      NavTwo
    },
    head(){
      return {
        title: "Indutri | Testimonials"
      }
    }
  }
</script>
