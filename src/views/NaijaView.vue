<template>
    <Naija/>
    <Footer1/>
</template>

<script>
import Naija from '@/components/Naija.vue';
import Footer1 from '@/components/Footer1.vue';


export default {
  name: 'PlacesView',
  components: { Naija, Footer1,
},
data:function(){
    return{
        intro:"Discover the cool hotels of Nigeria! There are so many places for you to enjoy your stay and rest! Add these cool hotels as your new home here today!"
    }
}
}
</script>