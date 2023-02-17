<template>
  <div class="content">
    <div class="todo-box">

    </div>
  </div>
</template>

<script>
export default {
  name: "Content"
}
</script>

<style scoped>

.content{
  background: linear-gradient(to top, white, 40%, orange);
  height: 1000px;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.todo-box{
  width: 900px;
  height: 800px;
  background-color: white;
  border-radius: 10px;
}

</style>