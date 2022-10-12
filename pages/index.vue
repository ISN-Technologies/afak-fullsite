<template>
  <div>
    <NavThree/>
    <SliderTwo/>
<!--    <NanoArea/>-->
    <SolutionArea/>
    <VideoArea/>
    <BuildingArea/>
    <BrandArea/>
<!--    <ClientArea/>-->
<!--    <FunFactArea/>-->
<!--    <ProjectArea/>-->
    <FaqBrandArea/>
    <FaqArea/>
    <FutureArea/>
    <FooterTwo/>
  </div>
</template>

<script>

import Slider from "../components/Slider";
import SliderTwo from "~/components/SliderTwo";
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

export default {
  components: {
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
