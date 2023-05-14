---
title: "The Prophet"
---

Author: Kahlil Gibran

<p id="typingEffect">Typing away my thoughts on this book <span id="loadingDots">...</span></p>

<script>
  // JavaScript code for the typing effect
  const typingElement = document.getElementById("typingEffect");
  const dotsElement = document.getElementById("loadingDots");

  let dotsCount = 0;
  const interval = setInterval(() => {
    dotsElement.textContent = ".".repeat(dotsCount % 4);
    dotsCount++;
  }, 500);

  typingElement.addEventListener("mouseenter", () => {
    clearInterval(interval);
    dotsElement.style.display = "none";
  });

  typingElement.addEventListener("mouseleave", () => {
    dotsCount = 0;
    dotsElement.style.display = "inline";
    interval = setInterval(() => {
      dotsElement.textContent = ".".repeat(dotsCount % 4);
      dotsCount++;
    }, 500);
  });
</script>

Coming soon! xD
