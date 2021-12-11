<template>
  <form>
    <div class="d-flex justify-content-between">
      <p class="masuk">Masuk</p>
      <p class="daftar">Daftar</p>
    </div>
    <input type="text" placeholder="Nomor Ponsel atau Email" />
    <input type="text" placeholder="Kata Sandi" />
    <button class="button btn">Masuk</button>
    <p><sub>Lupa kata sandi?</sub> <sub class="sub-text">Klik disini</sub></p>
    <div class="sub-header">
      <hr />
      <sub>atau masuk dengan</sub>
      <hr />
    </div>
    <div class="image-wrapper">
      <img
        src="~assets/images/Google.png"
        alt="right-side-image"
        class="image"
      />
      <div class="social">Google</div>
    </div>
    <div class="image-wrapper">
      <img
        src="~assets/images/Facebook.png"
        alt="right-side-image"
        class="image"
      />
      <div class="social">Facebook</div>
    </div>
  </form>
</template>

<script>
export default {};
</script>

<style scoped>
form {
  width: 70%;
  margin: 40px 5rem;
  padding: 2rem;
}
input {
  width: 100%;
  padding: 8px 3px;
  margin: 5px 0;
  color: #d0d0d0;
  font-size: 10px;
  border-radius: 5px;
  border: 1px solid #d0d0d0;
}
.masuk {
  font-weight: 500;
  color: #6f6f6f;
}
.daftar {
  font-size: 12px;
  font-weight: 500;
  color: #60bff2;
}
.button {
  padding: 10px 2rem;
  border-radius: 10px;
  background-color: #d0d0d0;
  color: white;
  width: 100%;
  font-weight: 700;
  text-align: center;
  transition: 0.5s;
  margin: 15px 0;
}
.button:hover {
  width: 15.5rem;
}
.sub-text {
  color: #60bff2;
}
.sub-header {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  color: #d0d0d0;
}
hr {
  width: 30%;
}
.image-wrapper {
  width: 100%;
  height: 32px;
  display: flex;
  justify-content: center;
  align-items: center;
  border: 1px solid #d0d0d0;
  margin: 10px 0;
  border-radius: 5px;
  cursor: pointer;
}
.image {
  width: 15px;
  height: 15px;
  object-fit: contain;
}
.social {
  font-size: 12px;
  padding-left: 4px;
  text-align: center;
  font-weight: 500;
}
@media (max-width: 1024px) {
  form {
    width: 100%;
    margin: 20px 0px;
  }
}
@media (max-width: 768px) {
  form {
    margin: 0;
  }
}
</style>
