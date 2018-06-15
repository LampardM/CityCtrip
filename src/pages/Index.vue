<template>
  <div class="select-box">
    <search-input></search-input>
  </div>
</template>

<script>
import SearchInput from '@/components/SearchInput'
import Scroll from '@/components/Scroll'
import CityList from '@/components/CityList'
import CityItem from '@/components/CityItem'
import PositionBox from '@/components/PositionBox'
import NavList from '@/components/NavList'

export default {
  name: "Index",
  components: {
    SearchInput,
    Scroll,
    CityList,
    CityItem,
    PositionBox,
    NavList
  },
  data() {
    return {
      
    };
  },
  mounted() {
  }
};
</script>

<style scoped>

</style>
