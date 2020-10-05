<template>
  <div class="card designcts">
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
.designcts {
  width: 370px;
  height: 315px;
}
</style>
