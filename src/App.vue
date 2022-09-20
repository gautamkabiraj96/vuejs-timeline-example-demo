<template>
  <div id="app">
    <timeline>
      <timeline-title>Established in 1997</timeline-title>
      <timeline-item bg-color="#ff0000"
        >Released first product in 1998</timeline-item
      >
      <timeline-item line-color="#0000ff" bg-color="#ffff00	" :hollow="false"
        >Released second product in 2002</timeline-item
      >
      <timeline-item font-color="#00ff00" :hollow="false"
        >Expanded to 500 workforce in 2004</timeline-item
      >
      <timeline-item :hollow="false"
        >Expanded to 3000 workforce in 2007</timeline-item
      >
      <timeline-item :hollow="false"
        >Expanded to 15 countries in 2012</timeline-item
      >
      <timeline-item :hollow="false"
        >Expanded to 40 countries 2015</timeline-item
      >
    </timeline>
  </div>
</template>

<script>
import { Timeline, TimelineItem, TimelineTitle } from "vue-cute-timeline";
import "vue-cute-timeline/dist/index.css";

export default {
  name: "App",
  components: {
    timeline: Timeline,
    "timeline-item": TimelineItem,
    "timeline-title": TimelineTitle,
  },
};
</script>