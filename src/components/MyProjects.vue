<template>
  <div>
    <!-- <h1>My projects</h1> -->
    <input type="text" v-model="todo">
    <button @click="add" v-if="arrayToDo.length <10">Add</button>

    <ul >
      <li v-for="(item, i) in arrayToDo" :key="i">
        <span>{{item}}</span>
        <button @click="remove(i)">Delete</button>
      </li>
    </ul>
  </div>
</template>

<script>

export default {
  name: "App",
  data () {
    return {
      message: "HomeWork-1",
      todo: "",
      arrayToDo: [],
// <!-- Homework end -->
      message2: "Additional - counter",
      counter: 0,
      // result: "",
    }
  },
  computed: {
  },
// <!-- Homework begin -->
  methods: {
    add() {
      if (this.todo){
        this.arrayToDo.push(this.todo);
        this.todo = "";
      }
  
    },
    remove(i){
      this.arrayToDo.splice(i, 1);
    },
// <!-- Homework end -->
    result () {
      return this.counter > 10 ? "Greater than 10": "Smaller than 10";
    },
    // increase () {
    //   this.counter ++;
    //   this.result = this.counter > 10 ? "Greater than 10": "Smaller than 10";
    // },
    // decrease () {
    //   this.counter --;
    //   this.result = this.counter > 10 ? "Greater than 10": "Smaller than 10";
    // }
  }
}


</script>

<style>

</style>