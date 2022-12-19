<template>
    <div>
        <h1>Your Folders</h1>
        <div class="parent">
            <NewFolderCard/>
            <FolderCard/>
            <FolderCard/>
            <FolderCard/>
            <FolderCard/>
            <FolderCard/>
            <FolderCard/>
            <FolderCard/>
            <FolderCard/>
            <FolderCard/>
            <FolderCard/>
            <FolderCard/>
          </div>
    </div>    
</template>
<script lang="ts">
import FolderCard from "../components/FolderCard.vue";
import NewFolderCard from "../components/NewFolderCard.vue"
export default {
    components: {
		FolderCard, NewFolderCard
	},
}
</script>
<style>
.parent {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-column-gap: 20px;
    grid-row-gap: 20px;
    }

h1 {
  color: #575460;
    font-family: 'Inter'; 
    font-size: 64px;
    text-align: center;
}
</style>
//    grid-template-rows: repeat(10, 1fr);