---
title: "Rio Furniture"
description: "this is meta description"
draft: false
image : "images/portfolio/work1.jpg"
bg_image: "images/feature-bg.jpg"
category: [ "UI/UX Design", "Video" ]
information:
  - label : "Client"
    info : "Jannie Kelonsky"
  - label : "What We Did"
    info : "Website Redesign"
  - label : "Tools Used"
    info : "Photoshop,Illustrator"
  - label : "Completed on"
    info : "17th March 2014"
  - label : "Skills"
    info : "HTML5 / PHP / CSS3"
  - label : "Client"
    info : "Jannie Kelonsky"
---

## Behance Website Redesign

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quas officiis cumque, harum dicta necessitatibus
reprehenderit, delectus molestiae, impedit alias adipisci distinctio voluptas. Tempora modi amet voluptate
at provident soluta consequatur.

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolores quibusdam sed, neque recusandae, est
odit. A facere tempore soluta laborum.

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Incidunt, rem eaque facilis. Sit, voluptas?
Error soluta odio, harum tenetur, alias in iure ipsam blanditiis illo, ratione, magnam a minima incidunt!
Suscipit facilis, ut maxime libero necessitatibus, rerum aut voluptates aliquam maiores iusto qui
temporibus nesciunt, incidunt in quasi. Veniam aliquid ea aperiam, obcaecati voluptate ab, temporibus
fugiat at, inventore molestiae quibusdam, modi numquam debitis libero aut eum. Architecto sit quia quidem
odit, quasi eveniet reprehenderit rerum dolorem voluptate sed aspernatur numquam enim, adipisci iste optio
ea libero laboriosam praesentium aperiam nobis vero tempore consequuntur sapiente eos at. Suscipit quis
voluptatibus temporibus dolore consectetur ex excepturi adipisci sunt. Maxime aperiam eos illum minima


  <title>Iframe Toggle Example</title>
  <style>
    /* CSS content here */
    /* Button styles */
    .button {
      background-color: white;
      color: black;
      padding: 10px;
      margin: 10px;
      cursor: pointer;
    }

    .button:hover {
      background-color: lightblue;
    }

    /* Iframe styles */
    #myIframe {
      transition: all 0.3s ease;
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
  <h2>Choose Iframe Size</h2>
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
