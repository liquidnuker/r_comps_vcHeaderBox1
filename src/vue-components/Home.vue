<template>
  <div>
  <!-- vcHeaderBox101 -->
  <h2 class="item-id">vcHeaderBox101</h2>
    <div class="row">
      <div class="col-sm-3">39</div>
      <div class="col-sm-9">
        <vcHeaderBox101 />
      </div>
    </div>

    <!-- vcHeaderBox102 -->
  <h2 class="item-id">vcHeaderBox102</h2>
    <div class="row">
      <div class="col-sm-3">39</div>
      <div class="col-sm-9">
        <vcHeaderBox102 />
      </div>
    </div>

  </div>
</template>
<script>
const vcHeaderBox101 = () => import ('./vcHeaderBox101.vue');
const vcHeaderBox102 = () => import ('./vcHeaderBox102.vue');
  export default {
    data () {
      return {    
      }
    },
    components: {
      vcHeaderBox101: vcHeaderBox101,
      vcHeaderBox102: vcHeaderBox102
    },
    mounted: function () {
      console.log("Home.vue mounted");
    }
  }
</script>