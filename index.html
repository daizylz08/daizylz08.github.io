<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Daizy - Hacker AI</title>
  <script src="https://w.soundcloud.com/player/api.js"></script>
  <style>
    body {
      margin: 0;
      font-family: monospace;
      background: black;
      color: white;
      overflow: hidden;
    }

    .card {
      position: relative;
      z-index: 10;
      background: rgba(0, 0, 0, 0.7);
      padding: 30px;
      border-radius: 15px;
      max-width: 400px;
      margin: 100px auto;
      box-shadow: 0 0 30px rgba(255, 0, 0, 0.5);
      text-align: center;
      border: 2px solid #ff0040;
    }

    .avatar {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #ff0040;
      margin-bottom: 15px;
    }

    h1 {
      font-size: 26px;
      color: #ff0040;
    }

    p {
      font-size: 16px;
      color: #ddd;
    }

    .links a {
      display: inline-block;
      margin: 10px 5px;
      padding: 10px 15px;
      background: #ff0040;
      color: #fff;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
      transition: background 0.3s;
    }

    .links a:hover {
      background: #ff3355;
    }

    canvas {
      position: fixed;
      top: 0;
      left: 0;
      z-index: 1;
      pointer-events: none;
    }

    #audio-control {
      position: fixed;
      bottom: 20px;
      right: 20px;
      z-index: 20;
      background: rgba(0, 0, 0, 0.6);
      padding: 10px 15px;
      border-radius: 10px;
      color: #ff0040;
      font-size: 14px;
      text-align: center;
    }

    #playBtn {
      background: #ff0040;
      color: white;
      padding: 8px 15px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-weight: bold;
    }

    #playBtn:hover {
      background: #ff3355;
    }
  </style>
</head>
<body>
  <canvas id="matrix-canvas"></canvas>

  <div class="card">
    <img src="https://png.pngtree.com/png-clipart/20230724/original/pngtree-coder-clipart-boy-working-with-computer-game-on-the-desk-vector-png-image_11072679.png" alt="Avatar" class="avatar" />
    <h1>Daizy2105</h1>
    <p>Sinh ngày 21/5/2008<br />Hà Nam - Hacker Social<br />Facebook unlocker & AI guy</p>
    <div class="links">
      <a href="https://facebook.com/daizylz.python" target="_blank">Facebook</a>
      <a href="https://zalo.me/0394778781" target="_blank">Zalo</a>
      <a href="https://github.com/yourusername" target="_blank">GitHub</a>
    </div>
  </div>

  <!-- Nhạc SoundCloud ẩn -->
  <iframe 
    id="scplayer"
    width="0" 
    height="0" 
    scrolling="no" 
    frameborder="no" 
    allow="autoplay"
    src="https://w.soundcloud.com/player/?url=https%3A//soundcloud.com/l-ng-tha-i/khi-m-nh-ng-x-o-hoa-ph-dung-cu&color=%23ff0040&auto_play=false&show_comments=false&show_user=false&hide_related=true&show_teaser=false&api=true">
  </iframe>

  <!-- Nút phát nhạc -->
  <div id="audio-control">
    Nhạc từ SoundCloud 🎶<br />
    <button id="playBtn">▶ Bấm để phát nhạc</button>
  </div>

  <script>
    const iframe = document.getElementById('scplayer');
    const widget = SC.Widget(iframe);

    document.getElementById("playBtn").addEventListener("click", () => {
      widget.play();
    });
  </script>

  <script>
    const canvas = document.getElementById("matrix-canvas");
    const ctx = canvas.getContext("2d");

    canvas.width = window.innerWidth;
    canvas.height = window.innerHeight;

    const pythonCode = "def hack_facebook(): return 'Unlocked' while True: print('Daizy2105')".split("");

    const fontSize = 16;
    const columns = canvas.width / fontSize;
    const drops = Array(Math.floor(columns)).fill(1);

    function drawMatrix() {
      ctx.fillStyle = "rgba(0, 0, 0, 0.05)";
      ctx.fillRect(0, 0, canvas.width, canvas.height);

      const colors = ["#ff0040", "#00ffee", "#ff4400", "#ff0077"];
      ctx.font = fontSize + "px monospace";

      for (let i = 0; i < drops.length; i++) {
        const text = pythonCode[Math.floor(Math.random() * pythonCode.length)];
        ctx.fillStyle = colors[Math.floor(Math.random() * colors.length)];
        ctx.fillText(text, i * fontSize, drops[i] * fontSize);

        if (drops[i] * fontSize > canvas.height && Math.random() > 0.975) {
          drops[i] = 0;
        }

        drops[i]++;
      }
    }

    setInterval(drawMatrix, 40);

    // Mouse trail particles
    const particles = [];

    class Particle {
      constructor(x, y) {
        this.x = x;
        this.y = y;
        this.size = Math.random() * 2 + 0.5;
        this.speedX = Math.random() * 2 - 1;
        this.speedY = Math.random() * 2 - 1;
        this.alpha = 1;
        this.color = ["#ff0040", "#00ffee", "#ff4400"][Math.floor(Math.random() * 3)];
      }

      update() {
        this.x += this.speedX;
        this.y += this.speedY;
        this.alpha -= 0.05;
      }

      draw() {
        ctx.globalAlpha = this.alpha * 0.3;
        ctx.beginPath();
        ctx.arc(this.x, this.y, this.size * 0.6, 0, Math.PI * 2);
        ctx.fillStyle = this.color;
        ctx.fill();
        ctx.globalAlpha = 1;
      }
    }

    function handleParticles() {
      for (let i = 0; i < particles.length; i++) {
        particles[i].update();
        particles[i].draw();
        if (particles[i].alpha <= 0) {
          particles.splice(i, 1);
          i--;
        }
      }
    }

    function animateParticles() {
      handleParticles();
      requestAnimationFrame(animateParticles);
    }

    animateParticles();

    window.addEventListener("mousemove", (e) => {
      for (let i = 0; i < 2; i++) {
        particles.push(new Particle(e.x, e.y));
      }
    });

    window.addEventListener("resize", () => {
      canvas.width = window.innerWidth;
      canvas.height = window.innerHeight;
    });
  </script>
</body>
</html>
