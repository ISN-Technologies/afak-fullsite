<template>
  <div>
    <NavThree />
    <PageHeader title="Projects" />
    <ProjectsPage />
    <FooterTwo />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import FooterTwo from "../components/FooterTwo";
  import PageHeader from "../components/PageHeader";
  import ProjectsPage from "../components/ProjectsPage";
  import NavTwo from "../components/NavTwo";
  import NavThree from "~/components/NavThree";
  export default {
    components: {
      NavThree,
      ProjectsPage,
      PageHeader,
      FooterTwo,
      NavTwo
    },
    head(){
      return {
        title: "AFAK Tanzania | Projects"
      }
    }
  }
</script>
