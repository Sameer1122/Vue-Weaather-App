<template>
  <header>
    <div class="container">
      <div class="logo">Weather App</div>
      <div class="links">
        <ul class="list">
          <li>Home</li>
          <li>Weather News</li>
        </ul>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
  component: {},
};
</script>

<style scoped>
header {
  background: #7f7fd5; /* fallback for old browsers */
  background: -webkit-linear-gradient(
    to right,
    #91eae4,
    #86a8e7,
    #7f7fd5
  ); /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(
    to right,
    #91eae4,
    #86a8e7,
    #7f7fd5
  ); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}
.container {
  display: flex;
  width: 90%;
  padding: 0.5rem 0rem;
  margin: auto;
  color: white;
  justify-content: space-between;
  align-items: center;
}
.list {
  display: flex;
  list-style: none;
}
.list li {
  margin-left: 16px;
}
</style>
