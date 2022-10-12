<template>
  <div>
    <NavThree />
    <PageHeader title="Our Mission, Vision and Values" />
    <SolutionTwoArea/>
    <CoreValues/>
    <FooterTwo />
  </div>
</template>

<script>

import Nav from "../components/Nav";
import FooterTwo from "../components/FooterTwo";
import PageHeader from "../components/PageHeader";
import TeamPage from "../components/TeamPage";
import CoreValues from "../components/CoreValues";
import MissionArea from "../components/MissionArea";
import NavTwo from "../components/NavTwo";
import SolutionTwoArea from "../components/SolutionTwoArea";
import NavThree from "~/components/NavThree";
export default {
  components: {
    NavThree,
    SolutionTwoArea,
    CoreValues,
    TeamPage,
    PageHeader,
    FooterTwo,
    NavTwo
  },
  head(){
    return {
      title: "AFAK Tanzania | Our Mission"
    }
  }
}
</script>
