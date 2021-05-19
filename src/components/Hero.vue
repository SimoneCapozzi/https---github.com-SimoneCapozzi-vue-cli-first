<template>

  <main>

    <div class="box1">
      <span class="testo">Ciao</span>
    </div>

    <div class="box2">
      <span>Vue</span>
    </div>

    <div class="box2">
      <span>Cli</span>
    </div>

  </main>

</template>

<script>
export default {
name: 'Hero'
}
</script>

<style>

main{
  width: 600px;
  height: 400px;
  background-color: green;
  margin: auto;
  margin-top: 100px;
  display: flex;
  justify-content: space-around;
  align-items: center;
  border: 1px solid black;
}

.box1{
  height: 100px;
  width: 100px;
  background-color: chartreuse;
  border: 1px solid black;
  display: flex;
  align-items: center;
}

.box2{
  height: 100px;
  width: 100px;
  background-color: chartreuse;
  border: 1px solid black;
  display: flex;
  align-items: center;
}

.box3{
  height: 100px;
  width: 100px;
  background-color: chartreuse;
  border: 1px solid black;
  display: flex;
  align-items: center;
}


span{
  color: blue;
  margin: auto;
  cursor: pointer;
}

</style>