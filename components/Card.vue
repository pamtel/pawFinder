<template>
  <div class="Hero">
    <div class="text-wrapper">
      <p class="header">Travling!</p>
      <Form />
      <footer>&copy; 2021 Travling. All Rights Reserved</footer>
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
  padding: 20px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  border-radius: 10px;
  background-color: #fff;
}
.text-wrapper {
  width: 50%;
  padding: 0 20px;
}
.header {
  font-weight: 700;
  font-size: 28px;
  color: #42a7c3;
}
.image {
  width: 27.5rem;
  border-radius: 10px;
  object-fit: cover;
}
footer {
  font-size: 12px;
  opacity: .7;
}
@media (max-width: 1024px) {
  .Hero {
    height: 100%;
    flex-direction: column-reverse;
    margin: 20px 0;
  }
  .text-wrapper {
    width: 100%;
  }
  .image {
    width: 100%;
    height: 100%;
    max-height: 500px;
  }
}
@media (max-width: 768px) {
  .text-wrapper {
    padding: 0;
  }
}
</style>
