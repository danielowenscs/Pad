<template>
    <div class="card">
        <div class="container">
          <Icon class="icon" icon="eva:folder-fill" width="32" color="#4AC76D"/>
          <div>Workouts</div>
        
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
    font-family: 'Inter'; 
    font-size: 26px;
    border-radius: 4px;
  }
  
  .card:hover {
    box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
  }
  
  .container {
    display: flex;
    width: 280px;
    height: 100px;
    padding-left: 24px;
    padding-right: 24px;
    padding-top: 34px;
    padding-bottom: 34px;
  }
.container > div {
  padding-left: 24px;
}


</style>