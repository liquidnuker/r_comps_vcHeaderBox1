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

  </div>
</template>
<script>
const vcHeaderBox101 = () => import ('./vcHeaderBox101.vue');
  export default {
    data () {
      return {    
      }
    },
    components: {
      vcHeaderBox101: vcHeaderBox101
    },
    mounted: function () {
      console.log("Home.vue mounted");
    }
  }
</script>