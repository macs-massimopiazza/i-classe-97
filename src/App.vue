<template>
  <h1 style="color: rgb(97 13 166); font-size: 4rem;">🎡🥰Vivaaaaa Classe 97🥰🎡</h1>
  <h3>yayaya</h3>
  <p style="color: #fa1afa">
    💕I vostri insegnanti e coordinatori: Luca, Simone, Giovanni, Massimox2 💕
  </p>
  <h3 style="color: #ff0f0f">🥰🤣😱🤧🎍🦖 Qualche parola 🥰🤣😱🤧🎍🦖</h3>
  <ul>
    <li v-for="(frase, index) in frasi" :key="index">
      {{ frase.testo }}
      <span style="font-style: italic"> -{{ frase.nome }}</span>
    </li>
  </ul>
  <img src="https://i.imgflip.com/7wsr35.jpg" alt="">
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      frasi: [
        { testo: "non dire sacco se non ce l'hai nel gatto", nome: "Massimo" },
        { testo: "io sono un gatto e non un sacco", nome: "Massimo" },
        { testo: "Un programmatore è in ritardo, si sta prepa...random()", nome: "Carlo" },
        { testo: "Ciao a tutti è stato un onore", nome: "Michele" },
        { testo: "Ciao sono un testo", nome: "Nicola" },
        { testo: "Sono un orco e questo è il mio fork-one", nome: "Shrek" },
        { testo: "Ciao a tuuutttttiiii", nome: "Jeremy" },
        { testo: "tutti per uno e uno per nessuno", nome: "Fabio" },
        { testo: "È proprio l'ora del tè con degli ottimi biscottini", nome: "Manuel"},
        { testo: "La pacchia è finita cit.", nome: "Gianbattista" },
        { testo: "qualcosa di emozionante", nome: "Alessandra" },
        
      ],
    };
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
}

body {
  background-color: #a4fbe5;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #5d00ff;
}

li {
  font-size: 20px;
  margin-bottom: 5px;
}

h1,
h3,
p,
ul {
  margin-bottom: 20px;
}

.proj {
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>
