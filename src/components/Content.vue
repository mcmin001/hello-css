<template>
  <div class="content">

    <div class="todo-box">

      <div class="todo-box-time">
        <p>星期二</p>
        <p>2023-02-21</p>
      </div>

      <div class="todo-input-div">
        <input class="todo-input" type="text">
        <button class="todo-input-add-btn">新增</button>
      </div>

      <div class="todo-title">
        你有1个待办事项
      </div>

      <div class="undo-list">
        <input type="checkbox" name="f" value="ff" class="undo-checkbox" id="checkbox1">
        <label class="undo-checkbox-label" for="checkbox1">fff</label>
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
input[type="checkbox"] {
  visibility: hidden;
}

.content {
  background: linear-gradient(to top, white, 40%, orange);
  height: 1000px;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.todo-box {
  width: 900px;
  height: 800px;
  background-color: white;
  border-radius: 10px;
}

.todo-box-time {
  width: 100%;
  background-color: aqua;
  height: auto;
  position: relative;
  display: inline-flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: flex-start;
  font-weight: bold;
  color: red;
  font-size: 20px;
  padding-left: 100px;
  box-sizing: border-box;
}

.todo-input-div {
  width: 100%;
  height: 50px;
  background-color: #888888;
  display: inline-flex;
  justify-content: space-between;
}

.todo-input {
  width: 600px;
  margin-left: 100px;
}

.todo-input-add-btn {
  width: 150px;
  margin-right: 100px;
}

.todo-title {
  color: red;
  margin-top: 10px;
  padding-left: 100px;
  font-size: 20px;
}

.undo-list {
  width: 100%;
  height: auto;
  background-color: aquamarine;
  display: flex;
  justify-content: left;
}

.undo-checkbox-label {
  display: block;
  width: 200px;
  height: 20px;
  margin-left: 100px;
  cursor: pointer;
  position: absolute;
  border: 1px solid #ccc;
}

</style>