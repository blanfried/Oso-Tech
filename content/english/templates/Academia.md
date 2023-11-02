---
title: "Academia"
description: "A Personal Website to Show Off Your Portfolio, Academic or Otherwise!"
draft: false
image : "images/portfolio/Academia-Template.jpg"
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

  <style>
    /* CSS content here */
    /* Button styles */
    .button {
      background-color: black;
      border-radius: 7px;
      color: white;
      padding: 10px;
      margin: 10px;
      cursor: pointer;
    }

    .button:hover {
      background-color: grey;
    }

    /* Iframe styles */
    #myIframe {
      transition: all 0.3s ease;
      border: 1px solid;
      border-radius: 5px;
    }

    #myIframe.desktop {
      width: 100%;
      height: 800px;
    }

    #myIframe.mobile {
      width: 80%;
      height: 500px;
    }
  </style>

  <!-- Markdown content rendered as HTML here -->
  <button class="button" id="mobileButton">Mobile/Tablet</button>
  <button class="button" id="desktopButton">Desktop</button>
  <iframe id="myIframe" class="mobile" src="https://osows.github.io/Academia/"></iframe>

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
