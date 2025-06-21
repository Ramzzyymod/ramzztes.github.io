<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Buy Panel Bot</title>
  <script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body, html {
      height: 100%;
      font-family: 'Arial Black', sans-serif;
      overflow: hidden;
    }

    #particles-js {
      position: fixed;
      width: 100%;
      height: 100%;
      background: #000;
      z-index: -1;
    }

    .splash {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100%;
      color: white;
      animation: fadeOut 1s ease 3s forwards;
      position: relative;
      z-index: 1;
    }

    .splash h1 {
      font-size: 2.5em;
      color: #00ccff;
      text-shadow: 0 0 20px #00ccff;
      margin-bottom: 20px;
    }

    .loader {
      border: 5px solid #333;
      border-top: 5px solid #00ccff;
      border-radius: 50%;
      width: 50px;
      height: 50px;
      animation: spin 1s linear infinite;
    }

    @keyframes spin {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }

    @keyframes fadeOut {
      to {
        opacity: 0;
        visibility: hidden;
      }
    }

    .main-content {
      display: none;
      color: white;
      padding: 20px;
      min-height: 100vh;
      position: relative;
      z-index: 1;
    }

    h1 {
      font-size: 2.5em;
      color: #00ccff;
      margin-bottom: 20px;
      text-align: center;
      animation: glow 2s infinite alternate;
    }

    @keyframes glow {
      from { text-shadow: 0 0 5px #00ccff; }
      to { text-shadow: 0 0 20px #00ccff; }
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
      margin: 20px 0;
    }

    .card {
      background: #111;
      border-radius: 15px;
      padding: 20px;
      box-shadow: 0 0 15px rgba(0,255,255,0.5);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .card:hover {
      transform: translateY(-10px);
      box-shadow: 0 0 25px rgba(255,255,255,0.6);
    }

    .card h2 {
      font-size: 1.4em;
      margin-bottom: 10px;
    }

    .features {
      text-align: left;
      margin-top: 10px;
      color: #66ccff;
      font-size: 0.9em;
    }

    .price {
      background: #00ccff;
      color: black;
      padding: 10px;
      margin-top: 10px;
      border-radius: 10px;
      font-weight: bold;
      font-size: 1.1em;
    }

    .btn {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 20px;
      background: #00ccff;
      color: white;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      transition: background 0.3s ease;
      text-decoration: none;
      font-weight: bold;
    }

    .btn:hover {
      background: #00ccff;
    }

    .contact a {
      color: #00ffcc;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <div id="particles-js"></div>
  <div class="splash" id="splash">
    <h1>Welcome to the private panel purchase website by Rofik</h1>
    <div class="loader"></div>
  </div>
  <div class="main-content" id="main">
    <h1>List Panel Private By Rofik</h1>
    <div class="cards">
     <div class="card">
        <h2>Panel 1gb</h2>
        <div class="features">
          <p>Ram 1gb , Cpu 40%</p>
        </div>
        <div class="price">1.000</div>
        <a class="btn" href="https://wa.me/6283169687238?text=Halo%20saya%20ingin%20beli%20panel%1gb%2020private%20seharga%201.000" target="_blank">Beli Sekarang</a>
      </div>
      <div class="card">
        <h2>Panel 2gb</h2>
        <div class="features">
          <p>Ram 2 , Cpu 60%</p>
        </div>
        <div class="price">2.000</div>
        <a class="btn" href="https://wa.me/6283169687238?text=Halo%20saya%20ingin%20beli%20panel%202gb%20private%20seharga%202.000" target="_blank">Beli Sekarang</a>
      </div>
      <div class="card">
        <h2>Panel 3gb</h2>
        <div class="features">
          <p>Ram 3 , Cpu 80%</p>
        </div>
        <div class="price">3.000</div>
        <a class="btn" href="https://wa.me/6283169687238?text=Halo%20saya%20ingin%20beli%20panel%203gb%20private%20seharga%203.000" target="_blank">Beli Sekarang</a>
      </div>
      <div class="card">
        <h2>Panel 4gb</h2>
        <div class="features">
          <p>Ram 4gb , Cpu 100%</p>
        </div>
        <div class="price">4.000</div>
        <a class="btn" href="https://wa.me/6283169687238?text=Halo%20saya%20ingin%20beli%20panel%204gb%20private%20seharga%204.000" target="_blank">Beli Sekarang</a>
      </div>
      <div class="card">
        <h2>Panel 5gb</h2>
        <div class="features">
          <p>Ram 5gb , Cpu 120%</p>
        </div>
        <div class="price">5.000</div>
        <a class="btn" href="https://wa.me/6283169687238?text=Halo%20saya%20ingin%20beli%20panel%205gb%20private%20seharga%205.000" target="_blank">Beli Sekarang</a>
      </div>
      <div class="card">
        <h2>Panel 6gb</h2>
        <div class="features">
          <p>Ram 6gb , Cpu 140%</p>
        </div>
        <div class="price">6.000</div>
        <a class="btn" href="https://wa.me/6283169687238?text=Halo%20saya%20ingin%20beli%20panel%206gb%20private%20seharga%206.000" target="_blank">Beli Sekarang</a>
      </div>
      <div class="card">
        <h2>Panel 7gb</h2>
        <div class="features">
          <p>Ram 7gb , Cpu 160%</p>
        </div>
        <div class="price">7.000</div>
        <a class="btn" href="https://wa.me/6283169687238?text=Halo%20saya%20ingin%20beli%20panel%207gb%20private%20seharga%207.000" target="_blank">Beli Sekarang</a>
      </div>
      <div class="card">
        <h2>Panel 8gb</h2>
        <div class="features">
          <p>Ram 8gb , Cpu 180%</p>
        </div>
        <div class="price">8.000</div>
        <a class="btn" href="https://wa.me/6283169687238?text=Halo%20saya%20ingin%20beli%20panel%208gb%20private%20seharga%208.000" target="_blank">Beli Sekarang</a>
      </div>
      <div class="card">
        <h2>Panel 9gb</h2>
        <div class="features">
          <p>Ram 9gb , Cpu 200%</p>
        </div>
        <div class="price">9.000</div>
        <a class="btn" href="https://wa.me/6283169687238?text=Halo%20saya%20ingin%20beli%20panel%209gb%20private%20seharga%209.000" target="_blank">Beli Sekarang</a>
      </div>
      <div class="card">
        <h2>Panel 10gb</h2>
        <div class="features">
          <p>Ram 10gb , Cpu 220</p>
        </div>
        <div class="price">10.000</div>
        <a class="btn" href="https://wa.me/6283169687238?text=Halo%20saya%20ingin%20beli%20panel%2010gb%20private%20seharga%2010.000" target="_blank">Beli Sekarang</a>
      </div>
      <div class="card">
        <h2>Panel Unlimited</h2>
        <div class="features">
          <p>Ram Unlimited , Cpu Unlimited</p>
        </div>
        <div class="price">12.000</div>
        <a class="btn" href="https://wa.me/6283169687238?text=Halo%20saya%20ingin%20beli%20panel%20unlimited%20private%20seharga%2012.000" target="_blank">Beli Sekarang</a>
    </div>
  </div>
  <script>
    setTimeout(() => {
      document.getElementById("splash").style.display = "none";
      document.getElementById("main").style.display = "block";
      document.body.style.overflow = "auto";
    }, 4000);
  </script>
  <script>
    particlesJS("particles-js", {
      particles: {
        number: { value: 80, density: { enable: true, value_area: 800 } },
        color: { value: "#00ccff" },
        shape: { type: "circle" },
        opacity: { value: 0.5 },
        size: { value: 3 },
        line_linked: {
          enable: true,
          distance: 150,
          color: "#00ccff",
          opacity: 0.4,
          width: 1
        },
        move: { enable: true, speed: 3 }
      },
      interactivity: {
        detect_on: "canvas",
        events: {
          onhover: { enable: true, mode: "repulse" },
          onclick: { enable: true, mode: "push" }
        },
        modes: {
          repulse: { distance: 100, duration: 0.4 },
          push: { particles_nb: 4 }
        }
      },
      retina_detect: true
    });
  </script>
</body>
</html>
