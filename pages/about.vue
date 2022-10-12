<template>
  <div>
    <NavThree />
    <PageHeader title="About Us" />
    <AboutPage />
<!--    <FunFactArea />-->
<!--    <ClientPage />-->
    <VideoArea />
<!--    <BrandArea />-->
<!--    <LeadershipPage />-->
    <ContactArea />
    <FooterTwo />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import FooterTwo from "../components/FooterTwo";
  import PageHeader from "../components/PageHeader";
  import AboutPage from "../components/AboutPage";
  import FunFactArea from "../components/FunFactArea";
  import ClientPage from "../components/ClientPage";
  import VideoArea from "../components/VideoArea";
  import BrandArea from "../components/BrandArea";
  import LeadershipPage from "../components/LeadershipPage";
  import ContactArea from "../components/ContactArea";
  import NavTwo from "../components/NavTwo";
  import MissionArea from "../components/MissionArea";
  import NavThree from "~/components/NavThree";
  import NanoArea from "@/components/NanoArea";
  export default {
    components: {
      NanoArea,
      NavThree,
      NavTwo,
      ContactArea,
      LeadershipPage,
      BrandArea,
      VideoArea,
      ClientPage,
      FunFactArea,
      AboutPage,
      PageHeader,
      FooterTwo,
      Nav
    },
    head(){
      return {
        title: "AFAK Tanzania | About Us"
      }
    }
  }
</script>
