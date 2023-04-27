

<script>

defineProps({
  msg: {
    type: String,
    required: true
    //teste
  }
})

  
</script>

<template>
    <button> {{msg}} </button>
</template>

<style scoped>
button{
  border-radius: 5px;
  color:white;
  background:green;
}
</style>