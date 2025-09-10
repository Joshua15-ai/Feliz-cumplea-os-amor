<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Feliz Cumpleaños, Xadani ❤</title>
  <style>
    :root{
      --bg:#140607; /* muy oscuro */
      --card:#1e0b0b;
      --accent:#7b0f0f; /* rojo profundo */
      --accent-2:#a51b1b;
      --text:#f6e9e9;
      --muted:#caa9a9;
    }
    html,body{height:100%;margin:0;font-family: "Inter", system-ui, -apple-system, Segoe UI, Roboto, "Helvetica Neue", Arial; background: radial-gradient(circle at 10% 10%, rgba(165,27,27,0.08), transparent 10%), linear-gradient(180deg,var(--bg), #120405 60%); color:var(--text);}
    .wrap{min-height:100%;display:flex;align-items:center;justify-content:center;padding:40px}
    .card{position:relative;width:min(980px,95%);border-radius:18px;padding:34px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));box-shadow:0 10px 40px rgba(0,0,0,0.6);overflow:hidden;border:1px solid rgba(165,27,27,0.12)}

    header{display:flex;gap:20px;align-items:center}
    .photo{width:120px;height:120px;border-radius:16px;background:linear-gradient(135deg,var(--accent),var(--accent-2));display:flex;align-items:center;justify-content:center;font-weight:700;font-size:18px;color:var(--text);box-shadow:0 8px 30px rgba(165,27,27,0.18)}
    h1{margin:0;font-size:28px}
    p.lead{color:var(--muted);margin-top:6px}

    .message{margin-top:22px;font-size:18px;line-height:1.5}
    .signature{margin-top:20px;font-weight:700;text-align:right;color:var(--muted)}

    /* corazones flotando */
    .hearts {position:absolute;inset:0;pointer-events:none;}
    .heart{position:absolute;left:50%;top:50%;opacity:0;transform-origin:center bottom}

    /* animación reusable para que suban y giren */
    @keyframes floatUp{
      0%{opacity:0;transform:translate(-50%,40px) scale(0.6) rotate(-10deg)}
      10%{opacity:1}
      100%{opacity:0;transform:translate(-50%,-420px) scale(1.15) rotate(20deg)}
    }

    /* tulipanes */
    .tulips{position:absolute;bottom:10px;left:14px;display:flex;gap:10px;align-items:flex-end;pointer-events:none}
    .tulip{width:46px;height:120px}

    /* controls */
    .controls{display:flex;gap:12px;align-items:center;margin-top:18px}
    .btn{background:transparent;border:1px solid rgba(255,255,255,0.06);padding:10px 14px;border-radius:12px;color:var(--text);cursor:pointer}
    .btn:hover{transform:translateY(-2px)}
    .volume{display:flex;gap:8px;align-items:center}
    input[type=range]{-webkit-appearance:none;width:160px;background:transparent}
    input[type=range]::-webkit-slider-runnable-track{height:6px;border-radius:6px;background:linear-gradient(90deg,var(--accent),var(--accent-2))}
    input[type=range]::-webkit-slider-thumb{-webkit-appearance:none;width:14px;height:14px;border-radius:50%;background:var(--text);box-shadow:0 2px 6px rgba(0,0,0,0.5)}

    footer{margin-top:22px;color:var(--muted);font-size:13px;text-align:center}

    /* responsive */
    @media (max-width:620px){
      .photo{width:86px;height:86px}
      h1{font-size:20px}
      .message{font-size:16px}
    }
  </style>
</head>
<body>
  <div class="wrap">
    <div class="card">
      <div class="hearts" aria-hidden="true">
        <!-- varios corazones con posiciones y delays diferentes -->
        <svg class="heart" style="left:12%;top:80%;animation:floatUp 9s linear infinite;animation-delay:0s;width:44px;" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M12 21s-7-4.5-9-8.5S4 3 12 7c8-4 9 5.5 9 5.5S19 16.5 12 21z" fill="#b51717"/></svg>
        <svg class="heart" style="left:30%;top:90%;animation:floatUp 11s linear infinite;animation-delay:1s;width:30px;" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M12 21s-7-4.5-9-8.5S4 3 12 7c8-4 9 5.5 9 5.5S19 16.5 12 21z" fill="#8b1010"/></svg>
        <svg class="heart" style="left:78%;top:92%;animation:floatUp 10s linear infinite;animation-delay:2s;width:50px;" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M12 21s-7-4.5-9-8.5S4 3 12 7c8-4 9 5.5 9 5.5S19 16.5 12 21z" fill="#c21a1a"/></svg>
        <svg class="heart" style="left:54%;top:85%;animation:floatUp 12s linear infinite;animation-delay:3s;width:36px;" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M12 21s-7-4.5-9-8.5S4 3 12 7c8-4 9 5.5 9 5.5S19 16.5 12 21z" fill="#a60f0f"/></svg>
      </div>

      <header>
        <div class="photo">X</div>
        <div>
          <h1>Feliz cumpleaños, Xadani ❤</h1>
          <p class="lead">Un regalo pequeño, hecho con todo mi cariño para tu día especial.</p>
        </div>
      </header>

      <section class="message" id="mensaje">
        <p>Mi querida Xadani,</p>
        <p>Hoy celebro el milagro de que existas. Cada risa tuya ilumina una habitación y cada silencio tuyo me enseña paciencia. Quisiera que este día esté lleno de momentos que te recuerden lo amada que eres: por mí, por quienes te conocen, y por la vida que te regaló otro año más.</p>
        <p>Tu nombre suena como promesa, y en mis pensamientos siempre encuentras un refugio. Gracias por ser luz, por tus abrazos sinceros y por cada gesto que me hace mejor. Si pudiera, detendría el tiempo para quedarme en este instante a tu lado.</p>
        <p>Que tus sueños bailen hoy con tulipanes, que el viento te cubra de petalos y que mi voz, aunque pequeña al lado del universo, te susurre que te amo.</p>
        <div class="signature">Con todo mi amor — Joshua ❤</div>
      </section>

      <div class="controls">
        <button class="btn" id="playBtn">▶ Reproducir canción</button>
        <button class="btn" id="pauseBtn">II Pausar</button>
        <div class="volume">
          <label for="vol">Vol:</label>
          <input id="vol" type="range" min="0" max="1" step="0.01" value="0.15" />
        </div>
        <button class="btn" id="fullscreenBtn">Abrir en pantalla completa</button>
      </div>

      <footer>Si la canción no suena automáticamente, presiona "Reproducir". Pon el archivo <strong>aquellos_ojos_verdes.mp3</strong> en la misma carpeta del HTML.</footer>

      <!-- tulipanes SVG -->
      <div class="tulips" aria-hidden="true">
        <!-- Tulip 1 -->
        <svg class="tulip" viewBox="0 0 120 320" xmlns="http://www.w3.org/2000/svg">
          <g transform="translate(10,20)">
            <path d="M40 260 C40 220 20 200 20 140 C20 80 60 40 60 40 C60 40 100 80 100 140 C100 200 80 220 80 260 Z" fill="#7b0f0f"/>
            <rect x="54" y="120" width="6" height="180" rx="3" fill="#1a3a1a" transform="rotate(-6 57 120)"/>
          </g>
        </svg>
        <!-- Tulip 2 -->
        <svg class="tulip" viewBox="0 0 120 320" xmlns="http://www.w3.org/2000/svg">
          <g transform="translate(10,10)">
            <path d="M40 260 C40 220 20 200 20 140 C20 80 60 40 60 40 C60 40 100 80 100 140 C100 200 80 220 80 260 Z" fill="#a51b1b"/>
            <rect x="54" y="120" width="6" height="180" rx="3" fill="#163116" transform="rotate(6 57 120)"/>
          </g>
        </svg>
        <!-- Tulip 3 -->
        <svg class="tulip" viewBox="0 0 120 320" xmlns="http://www.w3.org/2000/svg">
          <g transform="translate(10,5)">
            <path d="M40 260 C40 220 20 200 20 140 C20 80 60 40 60 40 C60 40 100 80 100 140 C100 200 80 220 80 260 Z" fill="#c21a1a"/>
            <rect x="54" y="120" width="6" height="180" rx="3" fill="#163116"/>
          </g>
        </svg>
      </div>

      <!-- Audio (pon tu archivo exactamente con este nombre en la misma carpeta) -->
      <audio id="audio" loop preload="auto">
        <source src="aquellos_ojos_verdes.mp3" type="audio/mpeg">
        Tu navegador no soporta audio HTML5. Coloca el archivo "aquellos_ojos_verdes.mp3" en la misma carpeta que este HTML.
      </audio>

    </div>
  </div>

  <script>
    const audio = document.getElementById('audio');
    const playBtn = document.getElementById('playBtn');
    const pauseBtn = document.getElementById('pauseBtn');
    const vol = document.getElementById('vol');
    const fsBtn = document.getElementById('fullscreenBtn');

    // Set initial low volume
    audio.volume = parseFloat(vol.value);

    playBtn.addEventListener('click', async ()=>{
      try{
        audio.volume = parseFloat(vol.value);
        await audio.play();
      }catch(e){
        console.log('No se pudo reproducir automaticamente',e);
        alert('Si el audio no inicia, permite reproducción o presiona el botón nuevamente.');
      }
    });
    pauseBtn.addEventListener('click', ()=>{audio.pause();});
    vol.addEventListener('input', ()=>{audio.volume = parseFloat(vol.value);});

    fsBtn.addEventListener('click', ()=>{
      if(!document.fullscreenElement){
        document.documentElement.requestFullscreen();
      } else {
        document.exitFullscreen();
      }
    });

    // pequeños efectos: hacer latir el corazón central con la música (si existe)
    const hearts = document.querySelectorAll('.heart');
    setInterval(()=>{
      hearts.forEach((h,i)=>{
        h.style.transform = `translate(-50%,0) scale(${1 + Math.random()*0.08}) rotate(${(Math.random()-0.5)*10}deg)`;
        h.style.opacity = 0.9 - Math.random()*0.3;
      })
    },600);

    .flor-interactiva {
  position: relative;
  width: 120px;
  margin: 30px auto;
  cursor: pointer;
  transition: transform 0.4s ease;
}
.flor-interactiva:hover {
  transform: scale(1.05);
}
.mensaje-flor {
  position: absolute;
  top: -40px;
  left: 50%;
  transform: translateX(-50%);
  background: var(--card);
  color: var(--text);
  padding: 8px 12px;
  border-radius: 12px;
  font-size: 14px;
  opacity: 0;
  transition: opacity 0.6s ease;
  pointer-events: none;
}
.flor-abierta #petalos {
  transform: scale(1.2) rotate(6deg);
  transform-origin: center;
  transition: transform 0.6s ease;
}
.flor-abierta .mensaje-flor {
  opacity: 1;
      }

      <!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>Tulipán Animado</title>
  <style>
    body {
      background: #140607;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .tulipan {
      width: 120px;
      animation: florecer 2.5s ease-out forwards;
      transform-origin: bottom center;
    }

    @keyframes florecer {
      0% {
        transform: scaleY(0.2) scaleX(0.8) rotate(-6deg);
        opacity: 0;
      }
      50% {
        transform: scaleY(1.1) scaleX(1.05) rotate(3deg);
        opacity: 1;
      }
      100% {
        transform: scale(1) rotate(0deg);
      }
    }
  </style>
</head>
<body>
  <svg class="tulipan" viewBox="0 0 120 320" xmlns="http://www.w3.org/2000/svg">
    <g transform="translate(10,20)">
      <path d="M40 260 C40 220 20 200 20 140 C20 80 60 40 60 40 C60 40 100 80 100 140 C100 200 80 220 80 260 Z" fill="#a51b1b"/>
      <rect x="54" y="120" width="6" height="180" rx="3" fill="#1a3a1a" transform="rotate(-6 57 120)"/>
    </g>
  </svg>
</body>
</html>
