# animales
Animales bonitos 
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Animales</title>

<style>
body{
    font-family: Arial, sans-serif;
    margin:0;
    background:#f5f5f5;
    text-align:center;
}

header{
    background:#4CAF50;
    color:white;
    padding:20px;
}

section{
    padding:20px;
}

.card{
    background:white;
    margin:20px auto;
    padding:20px;
    width:80%;
    border-radius:15px;
    box-shadow:0 4px 10px rgba(0,0,0,0.2);
}

img{
    width:250px;
    border-radius:15px;
}

button{
    background:#4CAF50;
    color:white;
    border:none;
    padding:10px 20px;
    border-radius:10px;
    cursor:pointer;
    font-size:16px;
}

button:hover{
    background:#45a049;
}
</style>
</head>

<body>

<header>
    <h1>🐾 Mundo Animal 🐾</h1>
    <p>Descubre animales increíbles</p>
</header>

<section>

<div class="card">
    <h2>León</h2>
    <img src="https://images.unsplash.com/photo-1546182990-dffeafbe841d?q=80&w=800&auto=format&fit=crop" alt="León">
    <p>El león es conocido como el rey de la selva.</p>
</div>

<div class="card">
    <h2>Panda</h2>
    <img src="https://images.unsplash.com/photo-1564349683136-77e08dba1ef7?q=80&w=800&auto=format&fit=crop" alt="Panda">
    <p>Los pandas son animales tranquilos y adorables.</p>
</div>

<button onclick="mensaje()">Haz clic</button>

</section>

<script>
function mensaje(){
    alert("¡Bienvenido al mundo animal!");
}
</script>

</body>
</html>