<script setup>
import cardCard from '../Card.vue'
</script>

<template>
    <div class="containerContainer">
    
        <cardCard />
        <cardCard />
        <cardCard />
        
    </div>
    <div class="cardBorder"></div>
</template>



<style lang="scss" scoped>
.containerContainer{
    display: flex;
    flex-wrap: 1;
    width: 100%;
    justify-content: space-evenly;

}
.cardBorder{
    border: 1px solid #333;


}

</style>