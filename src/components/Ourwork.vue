<template>
  <div class="card design1">
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
.design1 {
  width: 350px;
  height: 465px;
}
</style>
