<template>
  <div class="app-container">
    <div class="brush-container">
      <scatter />
      <area-bg />
      <area-dash />
    </div>
  </div>
</template>

<script>
import AreaBg from "./area-bg/index";
import AreaDash from "./area-dash/index";
import Scatter from "./scatter/index";
export default {
  name: "Translation",
  components: { AreaBg, AreaDash, Scatter },
  data() {
    return {};
  }
};
</script>
<style>
.brush-container {
  display: flex;
  flex-wrap: wrap;
}
.brush-container .brush-item {
  flex: 50% 0 0;
  margin-bottom: 30px;
}
.brush-container .brush-item .title {
  display: none;
  font-size: 20px;
  height: 60px;
  line-height: 60px;
  text-align: center;
}
.brush-container .brush-item .chart {
  width: 80%;
  min-width: 300px;
  max-width: 500px;
  margin: 0 auto;
  height: 400px;
}
</style>
