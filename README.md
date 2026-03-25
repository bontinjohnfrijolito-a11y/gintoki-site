<!DOCTYPE html>
<html lang="ht">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>GINTOKI IOS XIT - Top Up Free Fire Haiti</title>

<!-- SEO -->
<meta name="description" content="GINTOKI IOS XIT - Top Up Free Fire Haiti, Diamonds, NatCash, sèvis rapid ak sekirite.">
<meta name="keywords" content="gintoki ios xit, free fire top up haiti, diamonds haiti, natcash haiti, top up free fire">
<meta name="author" content="GINTOKI IOS XIT">

<!-- Google Verification (ou ka mete pita si ou vle) -->
<meta name="google-site-verification" content="">

<style>
html { scroll-behavior: smooth; }

body {
  margin:0;
  font-family: monospace;
  background:black;
  color:#00ffcc;
}

header {
  text-align:center;
  padding:15px;
  border-bottom:1px solid #00ffcc;
}

nav a {
  margin:10px;
  color:#00ffcc;
  text-decoration:none;
}

section {
  padding:40px;
  text-align:center;
}

.btn {
  padding:12px 25px;
  background:#00ffcc;
  border:none;
  cursor:pointer;
}

input, select {
  padding:10px;
  margin:10px;
}

.card {
  border:1px solid #00ffcc;
  margin:10px;
  padding:10px;
}

.whatsapp {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background: #00ffcc;
  padding: 15px;
  border-radius: 50%;
}
</style>
</head>

<body>

<header>
🔥 GINTOKI IOS XIT 💎

<nav>
  <a href="#home">Home</a>
  <a href="#topup">Top Up</a>
  <a href="#payment">Payment</a>
</nav>
</header>

<!-- HOME -->
<section id="home">
  <h1>GINTOKI IOS XIT - TOP UP HAITI 🔥</h1>
  <p>Top Up Free Fire • Fast • Secure • NatCash 💎</p>

  <a href="#topup">
    <button class="btn">ALE NAN TOP UP 🔥</button>
  </a>
</section>

<!-- TOP UP -->
<section id="topup">

<h2>💎 CHWAZI PACK</h2>

<select id="pack" onchange="updatePrice()">
<option value="175">100 + 10 Diamonds</option>
<option value="350">200 + 20 Diamonds</option>
<option value="500">310 + 31 Diamonds</option>
<option value="850">500 + 72 Diamonds</option>
<option value="1700">1000 + 166 Diamonds</option>
<option value="3500">2000 + 398 Diamonds</option>
<option value="8500">5000 + 1160 Diamonds</option>
</select>

<h3 id="price">Prix: 175 HTG</h3>

<input type="text" id="id" placeholder="Game ID"><br>

<p>📸 Apre peman, voye screenshot sou WhatsApp ✔️</p>

<button class="btn" onclick="sendWhatsApp()">VOYE KÒMAND 🔥</button>

</section>

<!-- PAYMENT -->
<section id="payment">

<h2>💳 METÒD PEMAN</h2>

<div class="card">
🟧 NatCash / MonCash<br><br>
📱 +509 32 31 6306<br>
👤 Joana Guillaume<br><br>
Voye screenshot apre peman ✔️
</div>

</section>

<a href="https://wa.me/50932316306" class="whatsapp">💬</a>

<script>
function updatePrice(){
 let price=document.getElementById("pack").value;
 document.getElementById("price").innerText="Prix: "+price+" HTG";
}

function sendWhatsApp(){
 let select=document.getElementById("pack");
 let pack=select.options[select.selectedIndex].text;
 let price=select.value;
 let id=document.getElementById("id").value;

 let message="Bonjou, mwen vle top up:\nID:"+id+
 "\nPack:"+pack+
 "\nPrix:"+price+" HTG\nM ap voye prèv peman.";

 let url="https://wa.me/50932316306?text="+encodeURIComponent(message);

 window.open(url,"_blank");
}
</script>

</body>
</html>
