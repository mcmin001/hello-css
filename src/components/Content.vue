<template>
  <div class="content">
    <div class="todo-box">
      <div class="todo-box-time">
        <p>星期二</p>
        <p>2023-02-21</p>
      </div>
      <div class="todo-input">
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
  flex-direction: column;
}

.todo-box{
  width: 900px;
  height: 800px;
  background-color: white;
  border-radius: 10px;
}

.todo-box-time{
  height: auto;
  position: relative;
  left:50px;
  top:50px;
  display: inline-flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: flex-start;
  font-weight: bold;
  color: red;
  font-size: 20px;
}

.todo-input{
  width: 300px;
  height: 100px;
  background-color: #888888;
}



</style>