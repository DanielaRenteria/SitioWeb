<template>
  <div id="app">
    <Header />
    <Nav />
    <Button></Button>
    <Boxs />
  </div>
</template>

<script>
import Nav from "../src/components/nav";
import Header from "../src/components/header";
import Button from "../src/components/button";
import Boxs from "../src/components/boxs";

export default {
  name: "App",
  components: {
    Nav,
    Header,
    Button,
    Boxs,
  },
};
</script>

<style></style>
