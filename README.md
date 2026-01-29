<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>King KB - Game Dadu</title>
  <style>
    body{
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg,#4facfe,#00f2fe);
      text-align:center;
      color:white;
      margin:0;
      padding:40px;
    }
    button{
      padding:15px 30px;
      font-size:18px;
      border:none;
      border-radius:10px;
      cursor:pointer;
    }
  </style>
</head>
<body>

<h1>🎲 KING KB 🎲</h1>
<p>Game Dadu Online</p>

<h2 id="hasil">Klik tombol</h2>
<button onclick="roll()">Lempar Dadu</button>

<script>
function roll(){
  let angka = Math.floor(Math.random()*6)+1;
  document.getElementById("hasil").innerText = "Hasil dadu: " + angka;
}
</script>

</body>
</html>
