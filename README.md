<!-- README.md Profile HTML -->
<h1 align="center">
  <span id="typing"></span>
  <span class="wave">👋</span>
</h1>

<h3 align="center">Aspiring UI/UX Designer</h3>

<p align="center">
  Crafting intuitive and visually appealing designs that bring ideas to life.
</p>

---

<h3 align="center">💌 Connect with me</h3>
<p align="center">
  <a href="https://facebook.com/yourprofile" target="_blank">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/facebook/facebook-original.svg" alt="Facebook" width="40" height="40"/>
  </a>
  <a href="https://instagram.com/yourprofile" target="_blank">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/instagram/instagram-original.svg" alt="Instagram" width="40" height="40"/>
  </a>
  <a href="mailto:your@email.com">
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Mail_%28iOS%29.svg" alt="Email" width="40" height="40"/>
  </a>
</p>

---

<h3 align="center">🛠 Tech Stack</h3>
<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/laravel/laravel-plain-wordmark.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" width="40" height="40"/>
</p>

<style>
  .wave {
    animation: wave-animation 2s infinite;
    transform-origin: 70% 70%;
    display: inline-block;
  }
  @keyframes wave-animation {
    0% { transform: rotate(0deg); }
    10% { transform: rotate(14deg); }
    20% { transform: rotate(-8deg); }
    30% { transform: rotate(14deg); }
    40% { transform: rotate(-4deg); }
    50% { transform: rotate(10deg); }
    60% { transform: rotate(0deg); }
    100% { transform: rotate(0deg); }
  }
</style>

<script>
  const text = "Hi, I'm Estela";
  let index = 0;
  function type() {
    if (index < text.length) {
      document.getElementById("typing").innerHTML += text.charAt(index);
      index++;
      setTimeout(type, 150);
    }
  }
  type();
</script>
