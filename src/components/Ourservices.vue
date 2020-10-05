<template>
  <div class="card design">
    <header>
      <slot name="header"></slot>
    </header>
    <main>
      <slot></slot>
    </main>
    <footer name="footer">
      <slot name="footer"></slot>
    </footer>
  </div>
</template>

<script>
export default {};
</script>

<style>
.design {

  width: 360px;
  height: 519px;
  border-radius: 10px;
  border: 1px solid;
}
</style>
