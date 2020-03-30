<template>
  <div class="display">
      {{value}}
  </div>
</template>

<script>
export default {
    props: ['value']
}
</script>

<style>
.display {
    grid-column: span 4;
    font-size: 2.1em;
    background-color: #0004;
    display: flex;
    justify-content: flex-end;
    align-items: center;
    padding: 20px;
    overflow: hidden;
}
</style>