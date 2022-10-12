<template>
  <div>
    <NavThree />
    <PageHeader title="Bridge construction" />
    <ProjectSingle />
    <FooterTwo />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import FooterTwo from "../components/FooterTwo";
  import PageHeader from "../components/PageHeader";
  import ProjectSingle from "../components/ProjectSingle";
  import NavThree from "@/components/NavThree";
  export default {
    components: {
      NavThree,
      ProjectSingle,
      PageHeader,
      FooterTwo,
      Nav
    },
    head(){
      return {
        title: "Indutri | Project Details"
      }
    }
  }
</script>
