<template>
  <div>
    <BlockHeaderPlain title="COVID-19 Statement">
      <template v-slot:side-content></template>
    </BlockHeaderPlain>
    <div class="main grey-background">
      <div class="et_pb_text_inner">
        <p>Our first priority will always be the safety and well-being of our community members. We are closely monitoring the developments of the Covid-19 pandemic, and how it may affect not only the conference, but the lives of our speakers, attendees, and organizers.</p>

        <p>No matter what happens, know that if you purchase a conference ticket, and decide not to attend, we will refund 100% of the paid price, up to 7 days before the conference starts.</p>

        <p>We will make a decision about postponing or cancelling the conference with enough time to allow for you to change or cancel your travel plans.</p>

        <p>The organizers are also committed to following all advice from authorities regarding large gatherings, and develop key prevention strategies if the conference is held as planned.</p>
      </div>
    </div>
    <DesktopFooter />
  </div>
</template>

<script>
    import BlockHeaderPlain from "../components/BlockHeaderPlain";
    import DesktopFooter from "../components/DesktopFooter";

    export default {
        name: "proposals",
        components: {DesktopFooter, BlockHeaderPlain},
    }
</script>

<style scoped lang="scss">
    @import 'assets/scss/settings';
    @import 'assets/scss/common';
    .menubar {
        position: relative;
        z-index: 1;
    }
    .main {
        padding: 100px;
    }
</style>
