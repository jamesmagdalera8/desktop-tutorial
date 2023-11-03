<template>
  <div>
    <h5 class="dash-board">{{ Title }}</h5>
  </div>
</template>

<script>
export default {
  name: "DashboardPage",

  data() {
    return {
      Title: "Dashboard",
    };
  },
};
</script>

<style>
.dash-board {
  margin: 5px auto;
  display: flex;
  justify-content: center;
  align-items: center;
  color: orangered;
}
</style>
