<template>
    <div class="card">
        <div class="container">
          <Icon class="icon" icon="eva:plus-outline" width="32" />
        </div>
      </div> 

</template>
<script lang="ts">
import { Icon } from '@iconify/vue';
export default {
	components: {
		Icon,
	},
}
</script>

<style scoped>
.card {
  
    width: 280px;
    background-color: #DEE3F2;
    color: #575460;
    border-radius: 4px;
  }
  
  .card:hover {
    box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
  }
  .container {
    display: flex;
    width: 280px;
    height: 100px;
    padding-left: 124px;
    padding-right: 124px;
    padding-top: 34px;
    padding-bottom: 34px;
  }



</style>