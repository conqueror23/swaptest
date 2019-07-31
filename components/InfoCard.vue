<template>
  <div>
    <Company v-bind:company="data.company"/>
    <TimeTable />
    <hr />
    <Location />
    <hr />
    <Contact />
    <hr />
    <div>
      <button></button>
      <button></button>
    </div>
  </div>
</template>

<script>
import data from "@/assets/constants/data";
import Company from "@/components/InfoCard/Company";
import TimeTable from "@/components/InfoCard/TimeTable";
import Location from "@/components/InfoCard/Location";
import Contact from "@/components/InfoCard/Contact";

export default {
  name: "InfoCard",
  components: {
    Company,
    Location,
    TimeTable,
    Contact
  },
  data() {
    return {
      data,
    };
  }
};
</script>

<style>
</style>
