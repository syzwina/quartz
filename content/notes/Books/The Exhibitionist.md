---
title: "The Exhibitionist"
---
This one ...  
This one deserves ALL my time so I am NOT going to do it now because I have exams coming up.  

But let me tell you, I felt enraged, disgusted, sad, and so so so MAD at the characters in this book.


<p id="typingEffect">Writing my heart out about this one <span id="loadingDots">...</span></p>

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
