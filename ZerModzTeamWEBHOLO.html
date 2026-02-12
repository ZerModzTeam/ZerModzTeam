<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ZerModzTeam</title>

<style>
body{
    font-family:Arial;
    margin:0;
    background:#f2f2f2;
}

header{
    background:black;
    color:white;
    text-align:center;
    padding:20px;
    position:relative;
    font-size:28px;
    font-weight:bold;
}

header .modz{
    color:red;
}

.admin-icon{
    position:absolute;
    right:20px;
    top:20px;
    font-size:22px;
    cursor:pointer;
}

.container{padding:20px;}

.card{
    background:white;
    padding:20px;
    border-radius:15px;
    margin-bottom:20px;
    box-shadow:0 5px 15px rgba(0,0,0,0.1);
    position:relative;
    transition:transform 0.3s, box-shadow 0.3s;
}

.card:hover{
    transform:translateY(-5px);
    box-shadow:0 10px 25px rgba(0,0,0,0.2);
}

.badge{
    position:absolute;
    top:15px;
    right:15px;
    background:red;
    color:white;
    padding:5px 10px;
    border-radius:20px;
    display:none;
    animation:blink 1s infinite;
    opacity:0;
    transition:opacity 0.5s;
}

@keyframes blink{
    0%{opacity:1;}
    50%{opacity:0.5;}
    100%{opacity:1;}
}

.harga-asli{
    text-decoration:line-through;
    color:gray;
    display:none;
    opacity:0;
    transition:opacity 0.5s;
}

.harga-promo{
    color:green;
    font-size:22px;
    font-weight:bold;
    transition:transform 0.3s, color 0.5s, opacity 0.5s;
    opacity:1;
}

.expired-label{
    font-size:12px;
    color:red;
    margin-top:4px;
    display:none;
    opacity:0;
    transition:opacity 0.5s;
}

button{
    margin-top:10px;
    padding:8px 15px;
    border:none;
    background:#25D366;
    color:white;
    border-radius:8px;
}

/* OVERLAY */
.overlay{
    display:none;
    position:fixed;
    top:0;
    left:0;
    width:100%;
    height:100%;
    background:rgba(0,0,0,0.6);
    justify-content:center;
    align-items:center;
    z-index:9999;
}

.box{
    background:white;
    padding:25px;
    border-radius:15px;
    width:300px;
    text-align:center;
}
</style>
</head>

<body>

<header>
<span>Zer<span class="modz">Modz</span>Team</span>
<div class="admin-icon" onclick="openLogin()">👤</div>
</header>

<div class="container">

<div class="card" data-id="1">
  <div class="badge">DISKON 🔥</div>
  <h3>HOLO ALL CHAR FFM</h3>
  <div class="expired-label"></div>
  <div class="harga-asli"></div>
  <div class="harga-promo" data-harga="22000">Rp 22.000</div>
  <button onclick="order('HOLO ALL CHAR FFM', this)">Order</button>
</div>

<div class="card" data-id="2">
  <div class="badge">DISKON 🔥</div>
  <h3>HOLO SENJATA FFM</h3>
  <div class="expired-label"></div>
  <div class="harga-asli"></div>
  <div class="harga-promo" data-harga="18000">Rp 18.000</div>
  <button onclick="order('HOLO SENJATA FFM', this)">Order</button>
</div>

<div class="card" data-id="3">
  <div class="badge">DISKON 🔥</div>
  <h3>HOLO SENJATA FFB</h3>
  <div class="expired-label"></div>
  <div class="harga-asli"></div>
  <div class="harga-promo" data-harga="15000">Rp 15.000</div>
  <button onclick="order('HOLO SENJATA FFB', this)">Order</button>
</div>

</div>

<!-- LOGIN -->
<div class="overlay" id="loginOverlay">
<div class="box">
<h3>Login Admin</h3>
<input type="text" id="user" placeholder="Username"><br><br>
<input type="password" id="pass" placeholder="Password"><br><br>
<button onclick="login()">Masuk</button>
</div>
</div>

<!-- ADMIN PANEL -->
<div class="overlay" id="adminOverlay">
<div class="box">
<h3>Diskon Per Produk (%) + Expired</h3>

Produk 1:<br>
<input type="number" id="d1" placeholder="Diskon (%)"><br>
<input type="datetime-local" id="e1" placeholder="Expired"><br><br>

Produk 2:<br>
<input type="number" id="d2" placeholder="Diskon (%)"><br>
<input type="datetime-local" id="e2" placeholder="Expired"><br><br>

Produk 3:<br>
<input type="number" id="d3" placeholder="Diskon (%)"><br>
<input type="datetime-local" id="e3" placeholder="Expired"><br><br>

<button onclick="setDiskon()">Simpan</button><br><br>
<button onclick="closeAdmin()">Tutup</button>
</div>
</div>

<script>
let nomor = "6289653938936";

/* FORMAT RUPIAH */
function formatRupiah(angka){
    return angka.toString().replace(/\B(?=(\d{3})+(?!\d))/g, ".");
}

/* AMBIL DISKON TERSIMPAN */
let diskonData = JSON.parse(localStorage.getItem("diskonData")) || {
    1: {diskon:0, expired:null},
    2: {diskon:0, expired:null},
    3: {diskon:0, expired:null}
};

/* LOGIN */
function openLogin(){
    document.getElementById("loginOverlay").style.display = "flex";
}

function login(){
    let u = document.getElementById("user").value;
    let p = document.getElementById("pass").value;

    if(u === "ZeroXitAndro" && p === "ROBB15"){
        document.getElementById("loginOverlay").style.display = "none";
        document.getElementById("adminOverlay").style.display = "flex";

        document.getElementById("d1").value = diskonData[1].diskon;
        document.getElementById("e1").value = diskonData[1].expired || "";
        document.getElementById("d2").value = diskonData[2].diskon;
        document.getElementById("e2").value = diskonData[2].expired || "";
        document.getElementById("d3").value = diskonData[3].diskon;
        document.getElementById("e3").value = diskonData[3].expired || "";

    } else {
        alert("Login salah!");
    }
}

function closeAdmin(){
    document.getElementById("adminOverlay").style.display = "none";
}

/* SET DISKON + EXPIRED */
function setDiskon(){
    diskonData[1] = {diskon: parseInt(document.getElementById("d1").value)||0, expired: document.getElementById("e1").value || null};
    diskonData[2] = {diskon: parseInt(document.getElementById("d2").value)||0, expired: document.getElementById("e2").value || null};
    diskonData[3] = {diskon: parseInt(document.getElementById("d3").value)||0, expired: document.getElementById("e3").value || null};

    localStorage.setItem("diskonData", JSON.stringify(diskonData));
    updateHarga();
    closeAdmin();
}

/* UPDATE HARGA + EFEK SMOOTH + POP EFFECT */
function updateHarga(){
    let now = new Date();

    document.querySelectorAll(".card").forEach(function(card){
        let id = card.getAttribute("data-id");
        let dData = diskonData[id];
        let diskonPersen = dData.diskon;

        // cek expired
        if(dData.expired && new Date(dData.expired) < now){
            diskonPersen = 0;
        }

        let hargaPromo = card.querySelector(".harga-promo");
        let hargaAsliText = card.querySelector(".harga-asli");
        let badge = card.querySelector(".badge");
        let expiredLabel = card.querySelector(".expired-label");

        let hargaAsli = parseInt(hargaPromo.getAttribute("data-harga"));
        let hargaFinal = Math.floor(hargaAsli - (hargaAsli * diskonPersen / 100));

        if(diskonPersen > 0){
            // fade in harga asli
            hargaAsliText.style.display = "block";
            hargaAsliText.style.opacity = 0;
            setTimeout(()=>{ hargaAsliText.style.opacity = 1; },50);

            // fade in badge
            badge.style.display = "block";
            badge.style.opacity = 0;
            setTimeout(()=>{ badge.style.opacity = 1; },50);

            // update harga promo dengan pop effect
            hargaPromo.style.transform = "scale(0.8)";
            hargaPromo.style.opacity = 0;
            setTimeout(()=>{
                hargaPromo.innerHTML = "Rp " + formatRupiah(hargaFinal);
                hargaPromo.style.opacity = 1;
                hargaPromo.style.transform = "scale(1.2)";
                setTimeout(()=>{ hargaPromo.style.transform = "scale(1)"; },200);
            },50);

            // expired label
            if(dData.expired){
                let expDate = new Date(dData.expired);
                if(expDate > now){
                    expiredLabel.style.display = "block";
                    expiredLabel.style.opacity = 0;
                    expiredLabel.innerText = "Expired: " + expDate.toLocaleString();
                    setTimeout(()=>{ expiredLabel.style.opacity = 1; },50);
                } else {
                    expiredLabel.style.display = "none";
                }
            }

        } else {
            hargaAsliText.style.display = "none";
            badge.style.display = "none";
            expiredLabel.style.display = "none";

            hargaPromo.style.transform = "scale(0.8)";
            hargaPromo.style.opacity = 0;
            setTimeout(()=>{
                hargaPromo.innerHTML = "Rp " + formatRupiah(hargaAsli);
                hargaPromo.style.opacity = 1;
                hargaPromo.style.transform = "scale(1)";
            },50);
        }
    });
}

/* ORDER */
function order(nama, btn){
    let card = btn.closest(".card");
    let hargaText = card.querySelector(".harga-promo").innerText;
    let pesan = "Halo kak saya mau order " + nama + " (" + hargaText + ")";
    window.open("https://wa.me/"+nomor+"?text="+encodeURIComponent(pesan));
}

/* AUTO REFRESH HARGA TIAP 5 DETIK */
setInterval(updateHarga, 5000);
</script>

</body>
</html>
