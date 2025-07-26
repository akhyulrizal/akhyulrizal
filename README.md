<!-- GitHub Profile README -->

<div align="center" style="background-color:#000; padding: 30px; border-radius: 12px;">
  
  <h1 style="color:#00ff99; font-family: monospace;">
    <span id="typed-text"></span><span id="cursor">|</span>
  </h1>

  <br/>

  <h3 style="color:#00ff99;">Can you help us to grow by sharing?</h3>

  <br/>

  <!-- Social Icons -->
  <a href="https://github.com/USERNAME" target="_blank">
    <img src="https://skillicons.dev/icons?i=github" width="40" />
  </a>
  <a href="https://linkedin.com/in/USERNAME" target="_blank">
    <img src="https://skillicons.dev/icons?i=linkedin" width="40" />
  </a>
  <a href="https://instagram.com/USERNAME" target="_blank">
    <img src="https://skillicons.dev/icons?i=instagram" width="40" />
  </a>

  <br/><br/>

  <!-- Email -->
  <p style="color:#ccc; font-size: 16px;">
    📧 myakhyulr@gmail.com
  </p>

</div>

<!-- Typing Animation -->
<script>
  const text = "Hi i'm Akhyul Rizal 👋";
  let i = 0;

  function typeWriter() {
    if (i < text.length) {
      document.getElementById("typed-text").innerHTML += text.charAt(i);
      i++;
      setTimeout(typeWriter, 100);
    }
  }

  window.onload = typeWriter;
</script>