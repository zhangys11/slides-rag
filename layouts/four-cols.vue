<template>
  <div class="slidev-layout four-cols">
    <div class="grid grid-cols-4 gap-4">
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
    </div>
  </div>
</template>

<style scoped>
.four-cols {
  padding: 1.5rem;
}
</style>