<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
     🤟🤟  𝑺𝒖𝒔𝒄𝒓𝒊𝒃𝒆𝒕𝒆 𝒚𝒂 𝒂𝒍 𝒄𝒂𝒏𝒂𝒍 𝒅𝒆 𝒀𝒐𝒖𝒕𝒖𝒃𝒆 𝑨𝒒𝒖𝒊 🤟🤟
      <a href="https://www.youtube.com/channel/UC8zVcmgagoXASGgzbkF588A" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    <h3>Vɪᴅᴇᴏs Dᴇsᴛᴀᴄᴀᴅᴏs Lɪɴᴋs</h3>
    <ul>
      <li>Quien es el Mejor Vocalista de Iron Maiden: <a href="https://www.youtube.com/watch?v=bHAa9aTHb80&t=7s" target="_blank" rel="noopener">Core Docs</a></li> <br/>
      <li>Phil Schneider<a href="https://www.youtube.com/watch?v=suPOKR1zyAQ&t=2s" target="_blank" rel="noopener">Forum</a></li><br/>
      <li>Cual es el Asecino Mas FREAK<a href="https://www.youtube.com/watch?v=27LPDeavF8w&t=12s" target="_blank" rel="noopener">Community Chat</a></li>
    </ul>
    
  </div>
</template>

<script>
export default {
  name: 'Eddie',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
h3{
  margin: 50px 0 0;
  background-color: tomato
}
</style>
