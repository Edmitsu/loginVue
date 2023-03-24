<template>
  <main class="main">
    <div class="navbar">
      <h1 class="main__title">Intergr<p class="main__title__logo">ALL</p>
      </h1>

    </div>
    <div class="form__container">
      <form class="form__login" action="">
        <input class="form__input" placeholder="Digite seu E-mail" type="email">
        <input class="form__input" placeholder="Digite sua Senha" type="password">
        <button class="form__submit" type="button"> LOGIN </button>
      </form>
    </div>
  </main>
</template>

<script>


export default {
  name: 'App',
  components: {

  }
}
</script>

<style>
* {
  font-family: Helvetica;
  padding: 0;
  margin: 0;
}

.main {
  display: flex;
  flex-direction: column;
  background: linear-gradient(#363738, #727c77);
  min-width: 100vw;
  min-height: 100vh;
  align-items: center;
  justify-content: center;
}



.main__title {
  display: flex;
  justify-content: center;
  position: fixed;
  top: 0;
  left: 0;
  font-style: italic;
  font-size: 3.5em;
  min-width: 100vw;
  text-align: center;
  color: beige;
  border-style: none;
  text-shadow: 0px 0px 0 rgb(228, 228, 203),
    0px 1px 0 rgb(212, 212, 187),
    0px 2px 0 rgb(195, 195, 170),
    0px 3px 0 rgb(178, 178, 153),
    0px 4px 3px rgba(0, 0, 0, 0.71),
    0px 4px 1px rgba(0, 0, 0, 0.5),
    0px 0px 3px rgba(0, 0, 0, .2);
}

.main__title__logo {
  color: red;
  text-shadow: 0px 4px 1px red,
    0px 0px 3px red;
}

.form__container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin: 1rem;
  padding: 1rem;
  border-radius: 2rem;
  background-color: #2c3e50;
  min-height: 50vh;
  max-width: 80vw;
  color: beige;
  -webkit-box-shadow: -2px 1px 40px 9px rgba(0, 0, 0, 0.6);
  -moz-box-shadow: -2px 1px 40px 9px rgba(0, 0, 0, 0.6);
  box-shadow: -2px 1px 30px 15px rgba(0, 0, 0, 0.6);
}

.form__login {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 1em;
  border-radius: 2em;
}

.form__input {
  border-radius: 2em;
  font-size: 1rem;
  min-height: 1.8em;
  min-width: 75vw;
  background-color: #6298cf;
  color: beige;
  border-style: none;
  box-shadow: -2px 1px 30px 15px rgba(81, 91, 207, 0.6);
}

.form__input::placeholder {
  text-align: center;
}

.form__submit {
  border-radius: 2em;
  font-size: 1rem;
  min-height: 1.8em;
  width: 40vw;
  padding: 0.4rem;
  background-color: #6298cf;
  color: beige;
  border-style: none;
  box-shadow: -2px 1px 30px 15px rgba(81, 91, 207, 0.6);
}
</style>
