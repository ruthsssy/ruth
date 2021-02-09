<template>
    <div class= "flex justify-center items-center h-screen bg-gray-200">
      <div class= "flex flex-col w-1/3">
         <div class="flex flex-wrap bg-white p-10 justify-start">
           <label class="w-full  font-bold text-xl text-black" for="department">Department</label>
           <input class="w-full border p-2 text-grey-darkest" type="department" name="department" id="department">
          </div>
      <div class="flex justify-end p-2 bg-gray-100">
      <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold p-2 rounded ">Create Department</button>
    </div>
  </div>
    </div>


</template>

<script>
export default {
  name: 'Department',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
