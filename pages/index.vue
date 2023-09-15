<template>
  <div>
    <NavThree/>
<!--    <Slider/>-->
    <SliderTwo/>
<!--    <NanoArea/>-->
<!--    <ProjectArea/>-->
    <ServicesArea />

<!--    <SolutionArea/>-->
    <VideoArea/>
<!--    <FunFactArea/>-->

    <BuildingArea/>
<!--    <BrandArea/>-->
<!--    <ClientArea/>-->
    <FaqBrandArea/>
    <FaqArea/>
    <FutureArea/>
    <FooterTwo/>
  </div>
</template>

<script>

import SliderTwo from "~/components/SliderTwo";
import Slider from "~/components/Slider";
import ServiceArea from "../components/ServiceArea";
import SolutionArea from "../components/SolutionArea";
import VideoArea from "../components/VideoArea";
import BuildingArea from "../components/BuildingArea";
import BrandArea from "../components/BrandArea";
import ClientArea from "../components/ClientArea";
import FunFactArea from "../components/FunFactArea";
import ProjectArea from "../components/ProjectArea";
import FaqBrandArea from "../components/FaqBrandArea";
import FaqArea from "../components/FaqArea";
import FutureArea from "../components/FutureArea";
import ProjectContactArea from "~/components/ProjectContactArea";
import FooterTwo from "../components/FooterTwo";
import NavThree from "~/components/NavThree";
import NanoArea from "~/components/NanoArea";
import ServicesArea from "~/components/ServicesArea.vue";

export default {
  components: {
    ServicesArea,
    NanoArea,
    NavThree,
    FooterTwo,
    FutureArea,
    FaqArea,
    ProjectContactArea,
    FaqBrandArea,
    ProjectArea,
    FunFactArea,
    ClientArea,
    BrandArea,
    BuildingArea,
    VideoArea,
    SolutionArea,
    SliderTwo,
  }
}
</script>
