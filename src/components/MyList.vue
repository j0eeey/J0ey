<template>
  <ul class="todo-main">
    <MyItem/>
  </ul>
</template>

<script>
import MyItem from "@/components/MyItem";
export default {
  name: "MyList",
  components: {MyItem}
}
</script>

<style scoped>

</style>