<template>
<div>
   <h1> {{name}}</h1> 
   <hr>
   <button @click="viewFullName()"> show full name </button>
</div>

</template>

<script>
export default {
  data: () => {
      return {
          name : "zũ",
      }
  },
  methods: {
        viewFullName() {
            this.name = "vu doan vv"
        }
  },
}
</script>

<style>

</style>
