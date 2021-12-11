<template>
  <div class="Hero">
    <div class="text-wrapper">
      <p class="header">Travling!</p>
      <!-- <button class="button btn">Start Looking</button> -->
    </div>
    <img
      src="~assets/images/SideRight.png"
      alt="right-side-image"
      class="image"
    />
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.Hero {
  max-height: 100vh;
  max-width: 1200px;
  overflow: hidden;
  position: relative;
  margin: 20px 0;
  padding: 20px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: #ffff;
  border-radius: 10px;
}
.text-wrapper {
  width: 50%;
  background-color: #ffff;
  padding: 0 20px;
}
.header {
  font-weight: 600;
  font-size: 28px;
  background-color: #ffff;
  color: #42a7c3;
}
.image {
  width: 27.5rem;
  border-radius: 10px;
}
.button {
  padding: 1rem 4rem;
  border-radius: 100rem;
  background-color: rgb(231, 81, 43);
  color: white;
  width: 20rem;
  font-weight: 700;
  transition: 0.5s;
}
.button:hover {
  width: 21.5rem;
}
@media (max-width: 768px) {
  .Hero {
    height: auto;
  }
}
</style>
