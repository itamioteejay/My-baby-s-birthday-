# <!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>For My Empress 👑</title>  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;1,300;1,400&family=Quicksand:wght@300;400;500&display=swap" rel="stylesheet"/>  <style>
    *, *::before, *::after { 
      margin: 0; 
      padding: 0; 
      box-sizing: border-box; 
    }

    :root {
      --gold: #c9a84c; 
      --gold2: #f0d080; 
      --soft: #e8dcc8;
      --dim: #9a8f7a; 
      --dark: #050810; 
      --mid: #0b0f1e;
      --font-d: 'Cormorant Garamond', serif;
      --font-b: 'Quicksand', sans-serif;
    }

    html {
      scroll-behavior: smooth;
      scroll-snap-type: y mandatory;
    }

    body {
      background: var(--dark); 
      color: var(--soft);
      font-family: var(--font-b); 
      font-weight: 300;
      overflow-x: hidden;
    }

    ::-webkit-scrollbar { width: 3px; }
    ::-webkit-scrollbar-thumb { background: var(--gold); }

    .no-scroll { overflow: hidden; }
    
    #entry-loader {
      position: fixed; 
      inset: 0; 
      background: var(--dark);
      z-index: 9999; 
      display: flex; 
      align-items: center; 
      justify-content: center;
      transition: opacity 1.5s, visibility 1.5s;
    }

    #entry-loader.hidden { 
      opacity: 0; 
      visibility: hidden; 
    }

    .loader-text {
      font-family: var(--font-d);
      font-size: clamp(1.5rem, 5vw, 2.5rem);
      font-style: italic; 
      color: var(--gold2);
      letter-spacing: .1em; 
      opacity: 0;
      animation: fadeInOut 2.5s ease-in-out forwards;
    }

    @keyframes fadeInOut {
      0% { opacity: 0; } 
      30% { opacity: 1; } 
      70% { opacity: 1; } 
      100% { opacity: 0; }
    }

    section {
      min-height: 100vh; 
      display: flex; 
      flex-direction: column;
      align-items: center; 
      justify-content: center;
      padding: 80px 28px 100px; 
      position: relative; 
      overflow: hidden;
      scroll-snap-align: start;
      scroll-snap-stop: always;
    }

    #s0 { background: radial-gradient(ellipse at 50% 55%, #0d1535, var(--dark)); }
    #s1 { background: #07090f; }
    #s2 { background: linear-gradient(160deg, #09101f, #0d1530); }
    #s3 { background: #08090f; }
    #s4 { background: linear-gradient(180deg, #090f1d, #060810); }
    #s5 { background: var(--mid); }
    #s6 { background: linear-gradient(160deg, #08101e, #0b1228); }
    #s7 { background: radial-gradient(ellipse at 50% 40%, #141a35, #070a12); }
    #s8 { background: radial-gradient(ellipse at 50% 55%, #0b1025, var(--dark)); }

    .box {
      max-width: 620px;
      text-align: center;
      z-index: 2;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .emp-img {
      width: 100%;
      max-width: 280px;
      aspect-ratio: 4/5;
      object-fit: cover;
      border-radius: 12px;
      border: 1px solid var(--dim);
      box-shadow: 0 8px 24px rgba(0, 0, 0, 0.5);
      margin-bottom: 24px;
    }

    .la {
      font-family: var(--font-d);
      font-size: clamp(1.4rem, 5vw, 2.2rem);
      font-style: italic; 
      color: #fff;
      margin-bottom: 8px;
    }

    .lt {
      font-family: var(--font-d);
      font-size: clamp(1.05rem, 3.8vw, 1.65rem);
      font-style: italic; 
      color: var(--gold2);
      margin-bottom: 4px;
    }

    .gap { margin-bottom: 30px; }

    .next-btn {
      display: inline-block;
      margin-top: 40px;
      padding: 12px 30px;
      border: 1px solid var(--gold);
      border-radius: 30px;
      background: transparent;
      color: var(--gold2);
      text-decoration: none;
      cursor: pointer;
      font-family: var(--font-b);
      transition: background 0.3s, color 0.3s;
    }

    .next-btn:hover {
      background: var(--gold);
      color: var(--dark);
    }
  </style></head><body class="no-scroll"><div id="entry-loader">
  <div class="loader-text">A universe built for you...</div>
</div><section id="s0">
  <div class="box">
    <img src="images/image1.jpg" alt="My Empress" class="emp-img">
    <p class="la">In a universe this vast…</p>
    <p class="la">I still found you</p>
    <a href="#s1" class="next-btn">Start</a>
  </div>
</section><section id="s1">
  <div class="box">
    <img src="images/image2.jpg" alt="My Empress" class="emp-img">
    <p class="la">Before you…</p>
    <p class="lt gap">things were just normal</p>
    <p class="lt gap">nothing really stood out like that</p>
    <p class="la">then you showed up…</p>
    <a href="#s2" class="next-btn">Next</a>
  </div>
</section><section id="s2">
  <div class="box">
    <img src="images/image3.jpg" alt="My Empress" class="emp-img">
    <p class="la gap">A beautiful tall girl…</p>
    <p class="lt">with that model-like posture</p>
    <p class="lt gap">the way you carry yourself — so effortless</p>
    <p class="lt">you don’t even try</p>
    <p class="la">but somehow… you still stand out every single time</p>
    <a href="#s3" class="next-btn">Next</a>
  </div>
</section><section id="s3">
  <div class="box">
    <img src="images/image4.jpg" alt="My Empress" class="emp-img">
    <p class="la gap">I love the way you talk</p>
    <p class="lt">you’re so good with your words</p>
    <p class="lt gap">like… you just know how to express yourself</p>
    <p class="la gap">and your voice…</p>
    <p class="lt">your voice is something else entirely</p>
    <p class="lt">it’s soft</p>
    <p class="lt gap">melodious</p>
    <p class="la gap">like God really took His time with you</p>
    <p class="lt">sometimes it actually feels like</p>
    <p class="lt">He sent an angel down…</p>
    <p class="lt">and gave her that voice</p>
    <a href="#s4" class="next-btn">Next</a>
  </div>
</section><section id="s4">
  <div class="box">
    <img src="images/image5.jpg" alt="My Empress" class="emp-img">
    <p class="la gap">you’re the first person in a very long time that made me feel like this</p>
    <p class="lt gap">and I don’t take that lightly at all</p>
    <p class="lt">you make me happy</p>
    <p class="lt gap">in ways I didn’t expect</p>
    <p class="la">even as someone who doesn’t really socialize like that…</p>
    <p class="lt">you changed that for me</p>
    <a href="#s5" class="next-btn">Next</a>
  </div>
</section><section id="s5">
  <div class="box">
    <img src="images/image6.jpg" alt="My Empress" class="emp-img">
    <p class="la gap">My lovely, beautiful, everlasting empress…</p>
    <p class="lt gap">you really are different</p>
    <p class="lt">the way you look</p>
    <p class="lt">the way you sound</p>
    <p class="lt gap">the way you carry yourself</p>
    <p class="la gap">everything about you just feels… special</p>
    <p class="lt gap">and yeah…</p>
    <p class="la">your ever glowing forehead 😭</p>
    <p class="lt">I’m not even joking —</p>
    <p class="lt">it’s actually elite</p>
    <a href="#s6" class="next-btn">Next</a>
  </div>
</section><section id="s6">
  <div class="box">
    <img src="images/image7.jpg" alt="My Empress" class="emp-img">
    <p class="la gap">all those late night talks…</p>
    <p class="lt">the random conversations</p>
    <p class="lt gap">the quiet moments</p>
    <p class="lt gap">even when we don’t always see things the same way</p>
    <p class="la">what matters is…</p>
    <p class="lt">I genuinely care about you</p>
    <a href="#s7" class="next-btn">Next</a>
  </div>
</section><section id="s7">
  <div class="box">
    <img src="images/image8.jpg" alt="My Empress" class="emp-img">
    <p class="la gap">today is yours</p>
    <p class="lt gap">and I just want to see you win in everything</p>
    <p class="lt">I pray God elevates you</p>
    <p class="lt">gives you more wisdom</p>
    <p class="lt">more knowledge</p>
    <p class="lt">more patience</p>
    <p class="lt gap">more happiness</p>
    <p class="lt">more money</p>
    <p class="lt gap">more blessings</p>
    <p class="la gap">more of everything you truly deserve</p>
    <p class="lt">and may all your heart’s desires be fulfilled</p>
    <a href="#s8" class="next-btn">Final</a>
  </div>
</section><section id="s8">
  <div class="box">
    <img src="images/image9.jpg" alt="My Empress" class="emp-img">
    <p class="lt gap">I’m always rooting for you</p>
    <p class="lt gap">always in your corner</p>
    <p class="la gap">your biggest fan… no matter what</p>
    <p class="lt gap">and honestly…</p>
    <p class="la">it’s you</p>
    <p class="lt gap">every time</p>
    <p class="la gap">my empress ❤️</p>
    <p class="la gap">I love you… all of you</p>
  </div>
</section><script>
window.addEventListener('load', () => {
  setTimeout(() => {
    document.getElementById('entry-loader').classList.add('hidden');
    document.body.classList.remove('no-scroll');
  }, 2000);
});
</script></body>
</html>
