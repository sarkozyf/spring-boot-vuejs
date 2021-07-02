<template>
  <div class="location">
    <h1>Create Location</h1>

  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
interface State {
  locations: {
    count: number;
  };
}
export default defineComponent({
  name: 'Locations',
  data: (): State => {
    return {
      locations: {
        count: 0
      }
    }
  },
  methods: {

  }
});
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1, h2 {
    font-weight: normal;
  }

  ul {
    list-style-type: none;
    padding: 0;
  }

  li {
    display: inline-block;
    margin: 0 10px;
  }

  a {
    color: #42b983;
  }
</style>
