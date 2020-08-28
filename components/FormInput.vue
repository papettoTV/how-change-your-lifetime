<template>
  <div>
    <b-form inline>
      <label>変わったこと</label>
      <b-input
        id="item"
        class="mb-2 mr-sm-2 mb-sm-0"
        placeholder="例）通勤時間"
      ></b-input>
      <label>変わった時間</label>
      <b-input id="change-time" placeholder="例）-1.5"></b-input>
      <b-icon-plus-circle></b-icon-plus-circle>
    </b-form>
    <b-button variant="primary">Save</b-button>
  </div>
</template>

<script>
import { BIconPlusCircle } from 'bootstrap-vue'

export default {
  components: {
    BIconPlusCircle,
  },
}
</script>
