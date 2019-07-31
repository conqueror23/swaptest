<template>
  <div>
    <b-card
      title="Card Title"
      img-src="https://picsum.photos/600/300/?image=25"
      img-alt="Image"
      img-top
      tag="article"
      style="max-width: 20rem;"
      class="mb-2"
    >
      <hr />
      <b-card-text>TimeTable</b-card-text>
      <hr />
      <b-card-text>location</b-card-text>
      <hr />
      <b-card-text>BranchInfo</b-card-text>
      <hr />

      <b-button href="#" variant="primary">No THANKS</b-button>
      <b-button href="#" variant="primary">I`LL TAKE IT</b-button>
    </b-card>
  </div>
</template>

<script>
import InfoCard from "@/components/InfoCard";
import Warper from "@/components/ContentWraper";
export default {
  name: "Content",
  components: {
    InfoCard,
    Warper
  }
};
</script>

<style>
</style>
