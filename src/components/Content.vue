<template>
  <div class="content">
    <div class="todo-box">
      <div class="todo-box-time">
        <br>星期二<br>
        2023-02-21
      </div>
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

.todo-box-time{
  width: 100px;
  height: 50px;
  background: #888888;
  position: relative;
  left:80px;
  top:80px;

}

</style>