<template>
  <router-view />
  <div class="go-top-container">
    <button id="go-top-button">
      <h3>Volver arriba</h3>
    </button>
  </div>
</template>

<script>

export default {
  name: 'App',

  //
}
</script>
<style scoped>
.go-top-container {
  position: fixed;
  bottom: 30px;
  right: 30px;
  opacity: 0;
  transition: opacity 0.3s;
}

.go-top-container.show {
  opacity: 1;
}

#go-top-button {
  background-color: transparent;
  box-shadow: unset;
  backdrop-filter: blur(10px);
  box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
  border-radius: 5px;
  padding: 10px 20px;
  border: 1px solid #7c3141;
  cursor: pointer;
  color: #7c3141;
}

#go-top-button:hover {
  background-color: rgb(174, 174, 174);
}

@media screen and (max-width: 950px) {
  .go-top-container {
    position: fixed;
    bottom: 40px;
    right: 55px;
    opacity: 0;
    transition: opacity 0.3s;
  }
}



@media screen and (max-width: 767px) {
  .go-top-container {
    display: none;
  }

  #go-top-button {
    display: none;
  }

}
</style>