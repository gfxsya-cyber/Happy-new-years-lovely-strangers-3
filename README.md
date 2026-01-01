# Happy-new-years-lovely-strangers-3
haiii, jangann lupa dibacaa sampaii akhir yyaa! semoga ini dapat menjadi kesan baik untuk kamuu
<!DOCTYPE html><html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Happy New Year ✨</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      font-family: 'Segoe UI', Tahoma, sans-serif;
      overflow: hidden;
    }.box {
  background: rgba(255, 255, 255, 0.95);
  max-width: 720px;
  padding: 40px;
  border-radius: 24px;
  box-shadow: 0 15px 35px rgba(0,0,0,0.25);
  animation: fadeIn 2s ease;
  z-index: 2;
}

@keyframes fadeIn {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}

h1 {
  text-align: center;
  color: #ff6fa5;
  margin-bottom: 20px;
}

p {
  color: #444;
  line-height: 1.8;
  font-size: 15px;
  margin-bottom: 14px;
}

.highlight {
  color: #ff6fa5;
  font-weight: 600;
}

.closing {
  text-align: center;
  margin-top: 30px;
  font-weight: 600;
  color: #555;
}

.heart {
  color: #ff6fa5;
}

/* Falling hearts */
.falling-heart {
  position: absolute;
  top: -10px;
  font-size: 18px;
  color: #ff8fb8;
  animation: fall linear infinite;
  opacity: 0.8;
}

@keyframes fall {
  0% { transform: translateY(0); opacity: 1; }
  100% { transform: translateY(110vh); opacity: 0; }
}

.music-note {
  position: fixed;
  bottom: 15px;
  right: 20px;
  font-size: 13px;
  color: #eee;
  opacity: 0.8;
}

  </style>
</head>
<body>  <!-- Background Music -->  <audio autoplay loop>
    <source src="https://cdn.pixabay.com/download/audio/2022/03/15/audio_7f1c2a8e0c.mp3?filename=romantic-piano-112191.mp3" type="audio/mpeg">
  </audio>  <!-- Hearts -->  <script>
    function createHeart() {
      const heart = document.createElement('div');
      heart.className = 'falling-heart';
      heart.innerText = '♡';
      heart.style.left = Math.random() * 100 + 'vw';
      heart.style.animationDuration = (3 + Math.random() * 4) + 's';
      document.body.appendChild(heart);

      setTimeout(() => {
        heart.remove();
      }, 7000);
    }

    setInterval(createHeart, 400);
  </script>  <div class="box">
    <h1>✨ Happy New Year ✨</h1><p><strong>Assalamualaikum wr. wb.</strong></p>

<p>
  Selamat malam, aa Izan. Mohon maaf mengganggu waktunya di malam hari ini.
  Semoga pesan kecil ini datang dengan cara yang lembut, seperti doa yang diam-diam menyusup ke hati.
</p>

<p>
  Perkenalkan, saya hanyalah seorang <span class="highlight">secret admirer</span>.
  Tidak ada nama, tidak ada identitas, dan memang tidak perlu.
  Karena yang ingin saya sampaikan bukan tentang siapa saya,
  melainkan tentang ketulusan yang ingin saya titipkan untuk aa.
</p>

<p class="highlight">HAPPY NEW YEARS! 🎉</p>

<p>
  Memang sedikit terlambat, tapi bukankah hal baik tidak pernah benar-benar salah waktu?
  Selama tahun baru masih terasa hangat di udara,
  semoga ucapan ini tetap punya tempat kecil di hati aa.
</p>

<p>
  Bagaimana hari pertama di tahun yang baru ini?
  Jika ada cerita—entah itu membahagiakan, melelahkan, atau sekadar biasa saja—
  semoga selalu ada ruang untuk bercerita dan didengarkan.
</p>

<p>
  Di tahun yang baru ini, saya mendoakan semoga aa selalu diberi kesehatan,
  pikiran yang lebih tenang, langkah yang lebih yakin,
  dan hati yang cukup kuat untuk menerima hal-hal baik yang sedang menuju aa.
</p>

<p>
  Terima kasih karena sudah membaca pesan ini sampai akhir.
  Tanpa aa sadari, itu sudah membuat pesan ini terasa sangat berarti.
</p>

<div class="closing">
  Once again, Happy New Year My Lovely Strangers! ✨<br />
  Be happy, be better, at your own pace.<br /><br />
  <span class="heart">♡</span> I love you, stranger <span class="heart">♡</span>
</div>

  </div>  <div class="music-note">🎶 musik romantis sedang diputar</div></body>
</html>
