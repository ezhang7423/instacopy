<template>
  <div>
    <img
      src="https://images-na.ssl-images-amazon.com/images/I/51QbFHJTguL.__AC_SX342_QL70_ML2_.jpg"
    />
  </div>
</template>
<script>
import * as data from "@/../data/obj_images2.js";

export default {
  name: "mprofile",
  components: {},
  //   data() {
  //       return: "";
  //   },
  // eslint-disable-next-line
  mounted: function() {
    console.log(data.fmtObj);
  }
};
</script>
