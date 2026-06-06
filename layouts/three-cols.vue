<template>
  <div class="slidev-layout three-cols">
    <div class="grid grid-cols-3 gap-4">
      <div class="col-1">
        <slot name="col1" />
      </div>
      <div class="col-2">
        <slot name="col2" />
      </div>
      <div class="col-3">
        <slot name="col3" />
      </div>
    </div>
  </div>
</template>