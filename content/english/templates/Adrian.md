---
title: "Adrian"
description: "A Personal Website to Show Off Your Portfolio, Academic or Otherwise!"
draft: false
image : "images/portfolio/Adrian-Template.jpg"
bg_image: "images/feature-bg.svg"
category: [ "Tier 2", "Personal" ]
information:
  - label : "Tier"
    info : "2"
  - label : "Price"
    info : "$399"
  - label : "Type of Website"
    info : "Personal"
  - label : "Time to Complete"
    info : "One week (on average)"
---

<!-- ## Title

  Further Description:
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quas officiis cumque, harum dicta necessitatibus
reprehenderit, delectus molestiae, impedit alias adipisci distinctio voluptas. Tempora modi amet voluptate
at provident soluta consequatur. -->


  <!-- Markdown content rendered as HTML here -->
  <button class="button" id="mobileButton">Mobile/Tablet</button>
  <button class="button" id="desktopButton">Desktop</button>
  <iframe id="myIframe" class="mobile" src="https://osows.github.io/Adrian/"></iframe>

  <script>
    // JavaScript content here
    document.getElementById('desktopButton').addEventListener('click', function() {
      var iframe = document.getElementById('myIframe');
      iframe.className = 'desktop';
    });

    document.getElementById('mobileButton').addEventListener('click', function() {
      var iframe = document.getElementById('myIframe');
      iframe.className = 'mobile';
    });
  </script>
