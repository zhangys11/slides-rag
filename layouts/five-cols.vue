<template>
  <div class="slidev-layout five-cols">
    <div class="grid grid-cols-5 gap-4">
      <div class="col-1">
        <slot name="col1" />
      </div>
      <div class="col-2">
        <slot name="col2" />
      </div>
      <div class="col-3">
        <slot name="col3" />
      </div>
      <div class="col-4">
        <slot name="col4" />
      </div>
      <div class="col-5">
        <slot name="col5" />
      </div>
    </div>
  </div>
</template>

<style scoped>
.five-cols {
  padding: 1.5rem;
}
</style>