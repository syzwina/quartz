---
title: "Three Dark Crowns"
---
Beltane. look this word up  


<p id="typingEffect">Typing my heart out on this one too <span id="loadingDots">...</span></p>

<script>
  // JavaScript code for the typing effect
  const typingElement = document.getElementById("typingEffect");
  const dotsElement = document.getElementById("loadingDots");

  let dotsCount = 0;
  let interval;

  function startAnimation() {
    interval = setInterval(() => {
      dotsElement.textContent = ".".repeat(dotsCount % 4);
      dotsCount++;
    }, 500);
  }

  typingElement.addEventListener("mouseenter", () => {
    clearInterval(interval);
    dotsElement.style.display = "none";
  });

  typingElement.addEventListener("mouseleave", () => {
    dotsCount = 0;
    dotsElement.style.display = "inline";
    startAnimation();
  });

  startAnimation();
</script>
