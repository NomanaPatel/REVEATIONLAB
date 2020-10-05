<template>
  <div class="d">
    <div class="columns">
      <div class="column">
        <div class="container pt-6">
          <div class="flex pt-6">
            <div class="sameRow">Content</div>
          </div>
          <div class="flex">
            <div class="sameRow">Content</div>
          </div>
          <div class="flex">
            <div class="sameRow">Content</div>
          </div>
        </div>
      </div>
      <div class="column">
        <div class="flex">
          <div class="sameRow1">Content</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>
<style>
.d {
  width: 800px;
  background-color: rgba(0, 198, 0, 0.1);
}
.container {
  width: 200px;
}
.flex {
  display: flex;
}
.sameRow {
  border: 2px solid black;
  height: 100px;
  width: 100%;
}
.sameRow1 {
  border: 2px solid black;
  height: 400px;
  width: 80%;
}

.normal {
  height: 40px;
  border: 2px solid red;
}
</style>
