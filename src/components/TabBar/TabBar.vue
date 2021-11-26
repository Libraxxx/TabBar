<template>
  <div id="tab-bar">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: "TabBar"
}
</script>


<style scoped>

#tab-bar {
  width: 100%;
  background-color: #f6f6f6;

  display: flex;
  justify-content: space-around;
  align-items: center;

  position: fixed;
  left: 0;
  bottom: 0;

  border-top: 1px solid #ccc;

}
</style>
