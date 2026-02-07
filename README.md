<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Mónica 💘</title>

<style>
body{
  margin:0;
  font-family: "Comic Sans MS", cursive;
  background: linear-gradient(#ff758c,#ffb199);
  height:100vh;
  display:flex;
  justify-content:center;
  align-items:center;
  overflow:hidden;
}

.card{
  background:white;
  padding:20px;
  border-radius:20px;
  text-align:center;
  box-shadow:0 10px 30px rgba(0,0,0,0.25);
  width:320px;
}

h1{
  color:#ff4d6d;
  font-size:22px;
}

/* Caricatura */
img{
  width:220px;
  border-radius:12px;
  margin-bottom:10px;
}

/* Botones */
button{
  padding:12px 22px;
  margin:8px;
  font-size:18px;
  border:none;
  border-radius:12px;
  cursor:pointer;
}

#yes{
  background:#ff4d6d;
  color:white;
}

#no{
  background:#ddd;
  position:relative;
}

/* Mensaje final */
#final{
  display:none;
  font-size:20px;
  color:#ff4d6d;
  margin-top:15px;
}

/* Corazones animados */
.heart{
  position:absolute;
  font-size:24px;
  animation:float 4s linear infinite;
}

@keyframes float{
  0%{transform:translateY(0);}
  100%{transform:translateY(-110vh);}
}
</style>
</head>

<body>

<!-- 🎵 Música romántica (cambia por tu canción) -->
<audio autoplay loop>
  <source src="musica.mp3" type="audio/mpeg">
</audio>

<div class="card">

<!-- 👩‍❤️‍👩 Caricatura de dos mujeres -->
<img src="https://i.imgur.com/3QZQZ7N.png">

<h1>🎮 Nivel Amor: Mónica 💘</h1>
<p>Mis sentimientos por ti subieron a nivel máximo 😳</p>
<p>¿Aceptas ser mi San Valentín?</p>

<button id="yes">Sí 💖</button>
<button
